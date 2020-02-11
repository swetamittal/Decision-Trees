# Decision-Trees

A decision tree is a graph that uses a branching method to illustrate every possible outcome of a decision.
 These are basically flowcharts in which decision is made at each level whih could divide the data into nodes which help in classification as well as making predictions. 
 
#Building Best Decision Tree

 Building a decision tree involves deciding on which feature to choose and what condition to use on splitting, alongwith knowing when to stop. In the first split on the root, all features are considered and the data points are divided into groups based on this split. Lets suppose, we have n features. Then we will be having n candidate splits at the first level. Now, we will calculate how much accuracy each split will cost us, using a function. The split(feature) which results in maximum accuracy is choosen at this level and data points are divided into child nodes according to that feature only. The child nodes formed are recursively divided into deeper levels, resulting in formation of the entire tree.
 
 In this project, I have implemented decision trees(self and inbuilt) on IRIS dataset.(A dataset containing three types of flowers).
