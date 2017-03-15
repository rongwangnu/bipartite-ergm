# bipartite-ergm
# ergm with two mode network data
# This file contains scripts to conduct bipartite ergm test
# It means that nodes in the newtork are two types
# The example I am using contains one set of nodes that are users, and one set of nodes that are teams
# The network ties indicate the team affiliation of users
# The script shows how to prepare network file (adj matrix) and attributes file
# Please note that in order for your bipartite model to run, you need to indicate what attributes are assigned to which type of nodes. 
# Otherwise, ERGM will run in some serious problems with missing data
