# Applied Bayesian Analysis (STA365 W24 UofT)

## [Course Learning Outcomes](https://tatp.utoronto.ca/teaching-toolkit/supporting-students/cdg/lesson-design/outcomes/#:~:text=The%20CTSI%20Guide%20on%20Developing,will%20be%20useful%20to%20them.)

- Ability to perform applied Bayesian analysis from simple to moderate complexity on real world data sets.
    - Bayesian analysis is generally considered the "gold standard" of uncertainty quantification since the Bayesian paradigm is predicated on careful specification of the data generating mechanism to fully capture the variability and dependency structure present within the data, and fully and coherrently propegating that uncertainty into parameter posterior inference.
    - Demonstrated capability in applied Bayesian analysis communicates to industry practitioners and academic researchers alike a strong understanding of and commitment to characterizing and respecting uncertainty
      during the data analysis process, and subsequently utilizing data driven information about uncertainty as part of downstream decision making efforts. 
- Ability to use Python and PyMC to implement Bayesian analyses, including creating specifications for unique data generating mechanisms and associated hierarchical modelling inference structures.
    - Python is an undeniably ubiquitous programming language present in both industrial and academic contexts, and can greatly faciliate the speed and scale at which data analyses can be carried out.
    - PyMC in particular is a highly popular probabilistic programming language which provides universal sampling of arbitrary data generating mechanisms and prior specifications
      that is generally effective and computationally efficient for many modeling and analysis purposes.
- Ability to evaluate, critque, and troubleshoot Bayesian modeling specifications and code producing Bayesian analyses, including assessing the influence of choices regarding priors and other modelling choices and decisions, interpreting model convergence and performance diagnostics, and providing posterior inference analysis and interpretation after modeling fitting and/or sampling and validation.
    - A true practitioner of Bayesian analysis must be able to assess, criticize, and utilize the inputs and outputs of a Bayesian posterior analysis
      since being unable to do so could result in unreliable and misleading statistical inference analysis and poor or wrong conclusions and decisions making.
- Gain familiarity with the historical development of Bayesian Analysis and exposure to its current advanced forms and manifestations, including modern Markov Chain Monte Carlo (MCMC) sampling methods such as
  Hamiltonian Monte Carlo (HMC), Langevin Monte Carlo (LMC), and Stochastic Gradient MCMC (SG-MCMC) as well as Bayesian Deep Learning (BDL).
    - While this is a course in "Applied" Bayesian analysis, some degree of familiarity with the more formal theoretrical aspects of the development of Bayesian analysis are expected of professional Bayesian
      practitioners, so familiarity and knowledge with the historical topics driving Bayesian analysis will be expected of analysts working in the field of Applied Bayesian analysis.
    - Many advanced modern Bayesian analysis methodologies such as HMC and the BDL techniques of "Bayes by Dropout" and "MC-Dropout" can actually be relatively quickly implemented and utilized,
      so having the ability to produce sophisticated cutting-edge data analyses by leveraging these tools affords a Bayesian practitioner the possibility to greatly extend the scope of their analysis capabilities
      in a relatively accessible manner.
      

## Tentative Weekly Topics
1. Bayes Theorem, Beta-Binomial, Bayesian bandit
2. Normal-Normal, Conjugate and other Priors
3. Gibbs sampling Normal-Gamma, Probabilistic Programming with `PyMC`, and Autocorrelation 
4. Metropolis-Hastings, Hamiltonian Monte Carlo, Diagnostics
     - Optional: Adaptive Squeezed Rejection Sampling and Slice Sampling
5. Bayesian Multiple Linear Regression, Inverse-Wishart and LKJ (Cholesky) priors and Multivariate Normal Distributions
6. Midterm
7. Reading Week
8. GLMs, Hierarchical Modeling, Multiplicity adjustment, Variable Selection, Shrinkage, Robust Regression  
9. Bayes Factors, Effective Model Size, Generalization/Overfitting, Model Selection (WAIC, LOO-CV, etc.), and Random Effects Models 
10. Mixture Models, Latent/Missing value imputation, and Variational Inference 
11. Gradient-based MCMC: SG-MCMC, LMC/SGLD
12. Bayesian Deep Learning (BDL)
13. Couse Projects


