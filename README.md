The rule for adding new edges to  consists of set of conditions and associated actions.  
If all the conditions are satisfied (on the Standard Dependency Graph), then a set of nodes are populated. 
Based on the populated nodes, user can write actions specifying between which nodes he/she wants to add edges. 
The set of conditions are based on Stanford Semgrex pattern (https://nlp.stanford.edu/nlp/javadoc/javanlp/edu/stanford/nlp/semgraph/semgrex/SemgrexPattern.html). 
The sets of conditions (semregex patterns) are applied to the dependency and it populates a set of nodes based on the pattern. 
Then the actions are applied to add new edges between the named nodes. 
Each Cond_# is Semregex Pattern
Each Action_# adds edges to comparison components
