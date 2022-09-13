# Election_Analysis

## Election Audit Results

Total Votes: 369,711

County Votes:
 - Jefferson: 10.5% (38,855)
 - Denver: 82.8% (306,055)
 - Arapahoe: 6.7% (24,801)
 
Largest County Turnout:
 - Denver

Candidate Result:
 - Charles Casper Stockham: 23.0% (85,213)
 - Diana DeGette: 73.8% (272,892)
 - Raymon Anthony Doane: 3.1% (11,606)
 
 Winner Result:
 - Winner: Diana DeGette
 - Winning Vote Count: 272,892
 - Winning Percentage: 73.8%
   
## Election Audit Summary

- The modification from the script of file_to_save = os.path.join("analysis", "Any_other_Election_Analysis.txt"),  with open(file_to_save, "w") as txt_anyfile: txt_anyfile.write(Any_other_Election_Analysis.txt) could create and edit any election results in a txt file.

-  The modification from the script counting the total votes number could count total votes number of any election results 
    
    for row in reader:
        
        total_votes = total_votes + 1
        
        other_candidate_name = row[3]
        
        if other_candidate_name not in candidate_options:
        
     candidate_votes[other_candidate_name] += 1  
     
