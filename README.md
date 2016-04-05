# CMTMicrosoftResearchUserScripts
A userscript to make bidding on CMT Microsoft Research easier.

When bidding on papers in Microsoft Conference Management Tool, the orinal interface does not provide a summary (number of bids per option). 

The script works on the bidding page where submissions are ordered by relevance. It tweaks two things:

* It creates a table with the number of bids for each bidding-option. Thus, users see how many bids they have entered.
* It orders the submissions by the assigned bidding option: "3-eager" first, then descending to "0-not willing" and afterwards all submissions without selection (ordered by relevance). Thus, users can go through those they have selected to adjust their ratings or through those they have not selected to bid on some of them.

