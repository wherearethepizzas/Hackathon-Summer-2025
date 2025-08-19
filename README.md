# University of Rochester Biomedical Data Science Hackathon Summer 2025
Welcome to the landing page for the hackathon. The event will run from 8/19/25 through 8/23/2025 online. If you missed the hybrid kickoff event on Monday 8/18, check your e-mail for the link to the recording.   

 Please make sure each individual competing on your team is fully registered. Each team needs a captain with a github handle. To receive a prize, you must supply your University of Rochester e-mail address. All teams scoring better than random will receive a participation prize. 1st and 2nd place winning teams in each division will get a cash prize (see below).
 **All team members must submit their own registration form to receive prizes.** To finish your team registration or to register for an existing team, use this [google form](https://docs.google.com/forms/d/e/1FAIpQLScDODn2UyefKIDaCjTlYF29xjRNgk2aJ98NtVksoDU1kFL44w/viewform?usp=sharing&ouid=101864452815264823434). 


# Logistics

0.   Each team must have a github handle associated with it in order to participate.  Make sure you edit your registration or email the organizers to provide this, if you haven't yet. Your team will not be scored if you do not provide a handle.
1.   You may add team members up
to noon EDT on 8/14 by editing your response to the google form or emailing the organizers.
2.  Teams of entirely undergraduates will be in the undergraduate
division, else they will be in the open division.
3.  Predictions on test data set are submitted by pushing to
    github.  A repository with the name `Hackathon-Summer-2025`,
    owned by the team captain, will
    be queried for a file named [prediction/prediction.csv](prediction/prediction.csv). Your predictions should be formatted in the exact same way and in the same order as the sample prediction file. Just replace the example TRUE/FALSE predictions with your own.  **If the team captain forks this
    repository and writes predictions there everything should work
    (as long as the predictions are formatted correctly).** 
2.  Predictions will be scored at least once daily, starting 8/20, with
    scores posted by 3 PM.  At
    the organizers' option, predictions may be scored more frequently
    than this.
2.  General questions/problems can be directed to [issues](https://github.com/Rochester-Biomedical-DS/Hackathon-Summer-2025/issues) page.  We encourage other hackathon participants to respond to issues.
3.  The scoreboard will be located
    [here](Leaderboard.Hackathon.2025.md).
   
    We  cannot provide support
    beyond the diagnostic output included on the scoreboard if an error is
    encountered in scoring your predictions.
5.  Interim scoring may employ forms of randomization (e.g. bootstrapping) from the test data set.  The final scores will use all the data and not be randomized.
4.  Competition runs through 2:59 PM EDT 23-August-2025.  The predictions each team has committed to their repository at that time will be used to determine their final score. Captains must submit their own predictions. Any use of predictions from other teams is disqualifying. Winning teams must submit their code to organizers to claim their prize.

**Overview**

- Genetic interactions are important for understanding human disease. Genetic interactions occur when the effects of perturbing two genes differ from what you’d predict based on either gene alone. An extreme example is a synthetic lethal pair, where knock out of either gene is viable and knock out of both genes is lethal. Genetic interactions are relevant to many human genetic diseases, particularly cancer where tumors often require combinations of multiple driver mutations in different genes. Genetic interactions are widespread but difficult to identify. A single genetic interaction can be tested by perturbing (knock out or over-expression) two genes separately and comparing this to a double perturbation. However, with ~20k human genes, there are far too many pairwise interactions to test experimentally (~4e+8).

- The goal of this hackathon is to predict gene expression when two genes are perturbed (over-expressed). Early work on this problem showed that double (two gene) perturbations could be predicted from single gene perturbations using gene expression data [PMC6746554](https://pubmed.ncbi.nlm.nih.gov/31395745/). For example, if two pathways need to be activated in order to get cell division, and activation of each pathway shows different gene expression signature, then one might be able to predict pairs of genes that activate both pathways by their individual gene expression profiles. This has led to significant interest and modeling efforts to predict the effects of single and double perturbations on gene expression.

- The data underlying this hackathon come from perturb-seq experiments. Perturb-seq pairs CRISPR-based screens with single-cell RNA sequencing. Each cell gets a different perturbation (over-expression of one or two genes) and the cell’s gene expression profile can be obtain from single-cell RNA-sequencing. Thus, similar to other single cell RNA sequencing (scRNA-seq) experiments, the data is sparse in that the expression of only a subset of genes is measured from each cell.

**Find a complete description of the dataset [here](Data.Description.md) and the data [here](/data).**

# Prizes
   
1.  First place in each division: $300 + $75 x (team size)
2.  Second place in each division: 0 + $50 x (team size)
  

