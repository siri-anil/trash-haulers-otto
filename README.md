## Missed Trash Pickups

In this data question you will be working data of service request related to missed trash pickups from hubNashville, Metro Nashville government's comprehensive customer service system (https://hub.nashville.gov).

As part of Metro's contract with Red River Waste Solutions, the failure to remedy an action or inaction would result in liquidated damages. One category of liquidated damages is related to chronic problems in any category of service at the same premises. A chronic problem is defined as three or more missed pickups at the same address in a 6 month time span. For each such incident, damages of $1500 results.  (A fine will be levied every time 3 unique dates occur within a 6 month time span)

Your job is to determine the total amount of damages due to missed pickups. Note that not all rows that you have been provided correspond to missed pickups and that you will need to ensure that you are only counting missed pickups.

After determining the total amount of damages, you can look at other questions:

* What other types of complaints are there?
* Make a heat map that shows the most total missed pick ups and another that shows the total fines, each by zip code.
* How do metro crews compare to the contractor's performance?
* How much does each trash hauler owe?
* What were to total missed pickup by route?
* The city is considering a different way to calculate fines by limiting the number of times a missed pickup can be counted towards a fine. If each date can only be used once per fine how will this difference impact the fines levied? (Example: If Jan 1st, Mar 3rd, Apr 8th, Aug 9th were the only 4 dates a trash pickup was missed the original method would result in $3000 in fines[Jan, Mar, Apr, and also Mar, Apr, Aug] however this updated method would only result in $1500 because neither Mar or Apr can be used for another fine because they were already used.)
