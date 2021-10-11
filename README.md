# Networks for Misinformation Research

The code in this repository contains the work I did in assisting Economics PhD candidate at UC Berkeley, Jimmy Narang, with his research into the way misinformation propogates throughout social networks. My work largely focused around building different types of networks in R and simulating how information can be shared between agents in a network. 
 
`networks_lib.Rmd` contains functions for different types of simple networks. The different types of network shapes covered are: 
1. Bipartite
2. Diamond
3. Spade 
4. Cycle
5. Pair 

These functions can be used to build off of each other and the function `simulate_and_animate` takes in a graph object and simulates how agents share information (through highlighting) for upto 5 different rounds of information sharing. 
