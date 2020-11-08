# CS446 Final Project brainstorm

## General ideas:
-   Something involving structural data: protein-drug interactions, protein structure and evolution, or otherwise
    -   Databases: SCOP, CATH, GO

## More specific ideas: (sub-steps in the project)

-   **Structural homology network**
    -   Network type: bipartite
    -   Nodes: proteins (by PDB ID)
    -   Secondary nodes: CATH designation (hierarchical?)
    -   Edges: structural CATH relations
    -   Databases: CATH or SCOP database, human PPI
    -   Tools: 
    -   Usefulness: 

-   **Network connecting ligand binding affinity and protein function**
    -   Network type: bipartite
    -   Nodes: proteins
    -   Secondary nodes: ligands these proteins bind
    -   Edges: interactions (weighted by interaction energy)
    -   Databases: PDBBind-CN, GO, human PPI
    -   Tools: QVina for docking (if information not available)
    -   Usefulness: Map ligand interactions to functional purpose, predict binding affinity using Naive Bayes prediction...?

-   **Metamorphicity analyzer**
    -   Network type: 
    -   Nodes: 
    -   Secondary nodes: 
    -   Edges: 
    -   Databases: 
    -   Tools: chen_sequence-based_2020; 
    -   Usefulness: 

-   **FSSP mapper**
    -   Network type: bipartite
    -   Nodes: proteins
    -   Secondary nodes: FSSP representative protein chains
    -   Edges: belonging of a protein to a specific structural family
    -   Databases: FSSP, human PPI
    -   Tools: 
    -   Usefulness: 

-   **Evolution distance mapper**
    -   Network type: 
    -   Nodes: 
    -   Secondary nodes: 
    -   Edges: 
    -   Databases: 
    -   Tools: 
    -   Usefulness: 

-   **Hierarchical protein structure network analyzer**
    -   Network type: two network types: one as described by PGR (computed for each structure), one as a tier describing connections between these subnetworks
    -   Net1 nodes: atoms in a single protein structure
    -   Net2 nodes: a protein, i.e. a collection of Net1 nodes
    -   Edges: interactions based on motif similarity between a lot of structures
    -   Databases: PGR, human PPI, larger?
    -   Tools: dhifli_pgr_2016
    -   Usefulness: 

### TEMPLATE

-   **Network descriptor**
    -   Network type: 
    -   Nodes: 
    -   Secondary nodes: 
    -   Edges: 
    -   Databases: 
    -   Tools: 
    -   Usefulness: 
    