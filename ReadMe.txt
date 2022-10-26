**R files**
Thyroid.DataClean.R is used to process data cleaning.


**Rnw Files**
SurvivalPlot.Rnw includes all survival plots except for TCGA data.
It includes
  Figures 1 D, E, F
  Figure 2 C
  Figures 7 A, B, C, D
  Supplement Figure 2 F
  Supplement Figures 15 A, B
  Supplement Figure 1 A (TERTp , TP53, PIK3CA)


Child.Cox.block.Rnw is a child document of the main document: SurvivalPlot.Rnw.

Fig7G.PenalizedLogisticRegression.Rnw is used to evaluate the association between aggression and a predictor. It includes Fig7G and odds ratios (saved as aggressive.OR.csv, not showed here) for forest plot in Supplement Figure 15F . 

Fig7H.PenalizedLogisticRegression.Rnw is used to assess the association between 'aggressive disease' and 'TP53, TERTp, PIK3CA mut+ATS'. It also includes Figure 7H.

Child.brglm2.block.Rnw is a child document of the main documents: Fig7G.PenalizedLogisticRegression.Rnw and Fig7H.PenalizedLogisticRegression.Rnw

Suppl.Fig15.F.Forestplot.Rnw is used to generate a forest plot in Supplement Figure 15F based on aggressive.OR.csv.



