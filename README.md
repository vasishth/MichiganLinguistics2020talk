# Computational models of retrieval processes: An evaluation using benchmark data

Shravan Vasishth ([vasishth.github.io](vasishth.github.io))

(Model development by: [Felix Engelmann](https://de.linkedin.com/in/felixengelmann), [Bruno Nicenboim](http://www.ling.uni-potsdam.de/~nicenboim/), [Lena Jäger](https://www.uni-potsdam.de/en/cs-ml/staff/phd/lenajaeger.html))

The talk will begin by revisiting the key predictions of the ACT-R based model of sentence processing ([Lewis and Vasishth, 2005](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog0000_25), henceforth LV05). As discussed in Engelmann, Jäger, and Vasishth, 2020, the LV05 model predicts two classes of similarity-based interference effects: inhibitory and facilitatory interference. Jäger, Engelmann, and Vasishth, 2017, carried out a meta-analysis of some 100 existing effect estimates (self-paced reading and eyetracking during reading). This work showed that the LV05 model's predictions are only partly consistent with the current evidence available. A closer look at the published data suggests that the published studies are likely to be severely underpowered. As Gelman and Carlin, 2014, have pointed out, when power is low, statistically significant effect estimates will be highly misleading: either the effects will be overestimated, or the sign of the effect will be incorrect (also see Vasishth, Mertzen, Jäger, and Gelman, 2018). Coupled with the problem of publication bias (in so-called high-impact journals, "big news" claims are published more often than "failed" studies or more tempered claims), these underpowered studies make theory evaluation difficult to impossible. What can we do as researchers? How to proceed? 

In the second part of the talk, I show one way that we can resolve these problems. In their classic paper, [Roberts and Pashler (2000)](https://psycnet.apa.org/fulltext/2000-15248-005.html) laid out two important criteria for model evaluation: the model needs to make quantitatively constrained predictions, and the effect estimates have to be measured with high precision. To these, we suggest one more criterion: model evaluation should always be carried out in the context of a competing baseline model to be meaningful. As a case study of model evaluation, we compare the predictive performance (using k-fold cross-validation) of the LV05 model with a competing model of retrieval processes, the McElree 2003 direct-access model (Nicenboim and Vasishth, 2018). The evaluation data-set is a relatively high-precision study on inhibitory interference effects in German number agreement (Nicenboim, Vasishth, Engelmann, and Suckow, 2018).   

I end with a brief discussion of ongoing work in my lab, which include 

- systematically developing higher-precision benchmark data for model evaluation;

- using approximate Bayesian Computation to arrive at realistic estimates of model parameters;  

- investigating the predictive performance of the LV05 and the direct-access model on individual-level effects in unimpaired controls as well as impaired populations (individuals with aphasia).  

Selected references

(All papers, including data and code, are available from: https://vasishth.github.io/publications.html)

Felix Engelmann, Lena A. Jäger, and Shravan Vasishth. The effect of prominence and cue association in retrieval processes: A computational account. Cognitive Science, 2020. 
https://onlinelibrary.wiley.com/doi/abs/10.1111/cogs.12800

Lena A. Jäger, Felix Engelmann, and Shravan Vasishth. Similarity-based interference in sentence comprehension: Literature review and Bayesian meta-analysis. Journal of Memory and Language, 94:316-339, 2017. 
https://www.sciencedirect.com/science/article/pii/S0749596X17300049

Lena A. Jäger, Daniela Mertzen, Julie A. Van Dyke, and Shravan Vasishth. Interference patterns in subject-verb agreement and reflexives revisited: A large-sample study. Journal of Memory and Language, 111, 2020. 
https://www.sciencedirect.com/science/article/pii/S0749596X19300956

Bruno Nicenboim and Shravan Vasishth. Models of retrieval in sentence comprehension: A computational evaluation using Bayesian hierarchical modeling. Journal of Memory and Language, 99:1-34, 2018. 
https://www.sciencedirect.com/science/article/pii/S0749596X16301577

Bruno Nicenboim, Shravan Vasishth, Felix Engelmann, and Katja Suckow. Exploratory and confirmatory analyses in sentence processing: A case study of number interference in German. Cognitive Science, 42, 2018. 
https://onlinelibrary.wiley.com/doi/full/10.1111/cogs.12589

Shravan Vasishth, Daniela Mertzen, Lena A. Jäger, and Andrew Gelman. The statistical significance filter leads to overoptimistic expectations of replicability. Journal of Memory and Language, 103:151-175, 2018. 
https://www.sciencedirect.com/science/article/pii/S0749596X18300640

Shravan Vasishth, Bruno Nicenboim, Felix Engelmann, and Frank Burchert. Computational models of retrieval processes in sentence processing. Trends in Cognitive Sciences, 23:968-982, 2019.
https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(19)30222-0  
