---
layout: paper
title: Improving the accuracy of demographic and molecular clock model comparison while accommodating phylogenetic uncertainty
image: /images/papers/baele-path-sampling.png
authors: Baele G, Lemey P, Bedford T, Rambaut A, Suchard MA, Alekseyenko AV.
year: 2012
ref: Baele et al. 2012. Mol Biol Evol.
journal: "Mol Biol Evol 29: 2157-2167."
pdf: /pdfs/papers/baele-path-sampling.pdf
doi: 10.1093/molbev/mss084
---

# Abstract

Recent developments in marginal likelihood estimation for model selection in the field of Bayesian phylogenetics and molecular evolution have emphasized the poor performance of the harmonic mean estimator (HME). Although these studies have shown the merits of new approaches applied to standard normally distributed examples and small real-world data sets, not much is currently known concerning the performance and computational issues of these methods when fitting complex evolutionary and population genetic models to empirical real-world data sets. Further, these approaches have not yet seen widespread application in the field due to the lack of implementations of these computationally demanding techniques in commonly used phylogenetic packages. We here investigate the performance of some of these new marginal likelihood estimators, specifically, path sampling (PS) and stepping-stone (SS) sampling for comparing models of demographic change and relaxed molecular clocks, using synthetic data and real-world examples for which unexpected inferences were made using the HME. Given the drastically increased computational demands of PS and SS sampling, we also investigate a posterior simulation-based analogue of Akaike's information criterion (AIC) through Markov chain Monte Carlo (MCMC), a model comparison approach that shares with the HME the appealing feature of having a low computational overhead over the original MCMC analysis. We confirm that the HME systematically overestimates the marginal likelihood and fails to yield reliable model classification and show that the AICM performs better and may be a useful initial evaluation of model choice but that it is also, to a lesser degree, unreliable. We show that PS and SS sampling substantially outperform these estimators and adjust the conclusions made concerning previous analyses for the three real-world data sets that we reanalyzed. The methods used in this article are now available in BEAST, a powerful user-friendly software package to perform Bayesian evolutionary analyses.    