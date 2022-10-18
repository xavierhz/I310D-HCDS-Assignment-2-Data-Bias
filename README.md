# I310D-HCDS-Assignment-2-Data-Bias

# Overview 
Using the Perspective API client to score the toxicity of each comment, I wanted to compare the toxicity scores of comments containing insults towards hispanic people and white people. 

Hypothesis: Perspective API will assign a higher toxicity score to insulting comments towards white people than those left towards hispanic people.

To compare the toxicity scores given to insulting comments by Perspective API, parallel comments towards white and hispanic people were created. I would like to note that I attempted to create a wide variety of comments, some even including slang we may see commonly used among gen z individuals. The submitted comments and their toxicity scores can found in the submitted-comments.txt file. 

For example, one comment may read "WHITE PEOPLE SUCK" while the other states "HISPANIC PEOPLE SUCK". The toxicity scores from these comments are then compared. 15 insulting comments towards white people and 15 insulting comments towards hispanic people will be analyzed. Therefore, the total sample size is 30 comments. 

Lists were created to store the toxicity scores given to insulting comments of both groups. The average of these scores was calculated to give us an idea if the Perspective AI gave an overall higher toxicity score to insulting comments towards white people than those of hispanic people. 

A bar chart comparing the toxicity score of insulting comments given to hispanic people and white people was created. The graph illustrated the majority of comments received a higher toxicity score when directed towards white people.

The insulting comments were then labeled as toxic or extremely-toxic based on their toxicity score. These labels were chosen due to the default negative nature of the comments. If a comment received a toxicity score between 0 and 0.5, it was considered toxic. If a comment received a toxicity score greater than 0.5, it was considered extremely toxic. 

A bar graph comparing the number of comments labeled as toxic and extremely toxic was created. In the graph, there were more insulting comments considered to be extremely toxic than toxic. 

# Results
After using the Perspective API client to score the toxicity of comments containing insults towards hispanic people and white people, the original hypothesis was supported by the analysis performed. Specifically, it was found that in most cases the Perspective API will assign a higher toxicity score to insulting comments towards white people than those left towards hispanic people. The average toxicity score of insulting comments towards white people was 0.6763. The average toxicity score of insulting comments towards hispanic people was 0.6448. 

Once the initial comparisons were made, the comments were labeled based on their toxicity score into two groups: toxic and extremely toxic. These labels were chosen as the created comments are insulting and negative in nature, therefore there are very low chances that a comment would be considered not toxic. If a comment scored less than or equal to 0.5 it was labeled as toxic. Any comment with a toxicity score greater than 0.5 was considered to be extremely toxic. Overall, there were 9 toxic comments and 21 extremely toxic comments. 

The results of our analysis support the idea that there may be potential bias within the Perspective API. Notably, comments made towards white people may take precedence over those made towards hispanic people. These biases may exist due to a lack of good training data for this specific group. Perspective's training data possibly contained more examples of comments involving white people than other minority groups. Therefore, it can only pick up patterns.
