# Prediction of drug side effects by observing similar sub-classes in the molecular structure of drugs

**Requirements before running the Notebook**  

A few models in the notebook require that it is run using GPU runtime.  
The datasets, drug_SMILES_750.csv and data1.txt must be loaded into the /content folder  

**Libraries**  
networkx : bipartite, degree_centrality, closeness_centrality, betweenness_centrality, projected_graph
matplotlib  
nxviz : CircosPlot  
torch  
torch_geometric : RandomLinkSplit, GCNConv, negative_sampling  
sklearn : StandardScaler, roc_auc_score  
torchdrug : datasets, core, models, tasks  

**Installations with versions**  
nxviz : nxviz-0.7.4-py3-none-any.whl  
cuda version installed : 1.11.0+cu113  
torch-scatter : 1.4.0  
torch-sparse  
pubchempy : PubChemPy-1.0.4.  
torchdrug : torchdrug-0.1.2.post1-py3-none-any.whl    

Link to PPT - https://drive.google.com/file/d/1Lamnhd1xF9I8Z-as7UvrFRecLrXdTZtr/view?usp=sharing  
Link to video explanation - https://drive.google.com/file/d/1QmH493TkergjAm5-J_tpEeZ5d5eHaYKT/view?usp=sharing  
