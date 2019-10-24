
![](https://miro.medium.com/max/385/1*WehLBuAwDKIsUQjb-97roA.png?raw=true)

## Background:
80% of producing oil wells in the United States are classified as stripper wells. Stripper wells produce low volumes at the well level, but at an aggregate level these wells are responsible for a significant percentage of domestic oil production.

Stripper wells are attractive to a company due to their low operational costs and low capital intensity - ultimately providing a source of steady cash flow to fund operations that require more funds to get off the ground.

At ConocoPhillips, our West Texas Conventional operations serve as a source of organic cash flow to fund more expensive projects in the Delaware Basin and other unconventional plays across the United States. As a company, it is vital that this steady, low cost form of cash has a constant presence.

As with all mechanical equipment, things break and when things break money is lost in the form of repairs and lost oil production. When costs go up cash goes down, but how can we predict when equipment will fail and use this information to drive down our costs?

## The Challenge:
A data set has been provided that has documented failure events that occurred on surface equipment and down-hole equipment. For each failure event, data has been collected from over 107 sensors that collect a variety of physical information both on the surface and below the ground.

Using this data, can we predict failures that occur both on the surface and below the ground? Using this information, how can we minimize costs associated with failures?

The goal of this challenge will be to predict surface and down-hole failures using the data set provided. This information can be used to send crews out to a well location to fix equipment on the surface or send a workover rig to the well to pull down-hole equipment and address the failure.

In addition to uploading a solution file (described in "Evaluation"), teams will be asked to provide a "kernel" via a markdown file. The kernel provides us with your code and output in addition to answers for the prompts in the "Kernels Requirements" section. These prompts in the "Kernels Requirements" section will determine your team's overall placement in the competition.

## Conclusion
We were able to achieve an accuracy of 95% and a F-1 score of 94.5% by using a Random Forest Classifier and GridSearchCV for hyper parameter tuning.
