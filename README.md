## Problem Description

Now that we have explored the data and looked at how to handle missing values, the next step is to build a classification model to predict days with low humidity. Recall that low humidity is one of the weather conditions that increase the dangers of wildfires, so it would be helpful to be able to predict low-humidity days. We will build a decision model to classify low-humidity days vs. non-low-humidity days based on weather conditions observed at 9am.

## Tools Used

1. KNIME Analytical Platform
2. Decision Tree Classification Learning Algorithm

## Model WorkFlow and Pipeline

![](https://1.bp.blogspot.com/-GIkX_UGF27Q/X1JrCqb8iuI/AAAAAAAAU0M/N3MmNci5S_kdBorrpPuS2DANCCL_iCxzACLcBGAsYHQ/w781-h248/workflow.png)

## Interpreting Model

`First Look at the Tree Structure given below, I am going to interpret from that structure only. Look Carefully :) `

1. Tree Structure : Please not red color means low humidity days. Also note that i am only expanding low humidity days.

![](https://1.bp.blogspot.com/-mlhqJJCUr3o/X1JrN-khxtI/AAAAAAAAU0U/z1790VIGY5c3UoUGR9ea1t8bIgeMq37BgCLcBGAsYHQ/w936-h976/tree.png)

2. Simple Tree Structure : Please not red color means low humidity days. Also note that i am only expanding low humidity days.

![](https://1.bp.blogspot.com/-BZz9e1rDxJY/X1JshRjXJyI/AAAAAAAAU0k/s4mp5TfWOKERUjcKuirBUmhlughhIZQZwCLcBGAsYHQ/w781-h455/tree%2Bsimple.png)
