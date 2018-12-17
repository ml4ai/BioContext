# Inferring Biological Context from Text
This repository is the homepage for all data and code associated with the UA Big Mechanism projects biological context project. 

The main goal of this project is to correctly link biological events and biological context containers that have been extracted from Biomedical publications.


## Obtaining our code and data
- The code for our project is available in the [experimentation repository](https://github.com/ml4ai/BioContext_experiment). This repository includes all the documentation necessary to replicate our published findings from our [DMBIH](http://facweb.cs.depaul.edu/research/vc/ICDM18/index.html) workshop paper submission (in coordination with [ICDM](http://icdm2018.org/workshop/)).

- The annotations used for the experiment are available in the [corpus repository](https://github.com/ml4ai/BioContext_corpus). This repository contains the information extraction annotations, the domain expert annotations in a format ready to be consumed by the code of the experimentation repository.

- For replication of results associated with our ablation study we have made our [ablation data](https://github.com/ml4ai/BioContext_results) available as well, so that those without the computational resources to conduct an ablation study can still replicate our additional results.

## Dataset description
We obtained our corpus of Biomedical papers from PubMed Central. Below is a table of the PMCIDs for each of our 22 papers along with the paper titles. The PMCIDs can be used to find the original papers that are available on PubMed.

| PMCID | Paper title |
| ------------- | ------------- |
| [PMC2743561](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2743561/) | Persistent DNA damage signaling triggers senescence-associated inflammatory cytokine secretion |
| [PMC3203906](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3203906/) | Phosphoinositide 3-Kinaseγ Controls the Intracellular Localization of CpG to Limit DNA-PKcs-Dependent IL-10 Production in Macrophages  |
| [PMC534114](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC534114/)  | The docking protein Gab1 is the primary mediator of EGF-stimulated activation of the PI-3K/Akt cell survival pathway |
| [PMC2193052](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2193052/) | Grf40, A Novel Grb2 Family Member, Is Involved in T Cell Signaling through Interaction with SLP-76 and LAT |
| [PMC3032653](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3032653/) | Spatially restricted activation of RhoA at epithelial junctions by p114RhoGEF drives junction formation and morphogenesis |
| [PMC2978746](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2978746/) | Regulation of C/EBPbeta1 by Ras in mammary epithelial cells and the role of C/EBPbeta1 in oncogene-induced senescence |
| [PMC3717960](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3717960/) | Up-regulation of c-MYC and SIRT1 expression correlates with malignant transformation in the serrated route to colorectal cancer |
| [PMC3461631](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3461631/) | The Role of Semaphorins and Their Receptors in Gliomas |
| [PMC2195994](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2195994/) | Cdc42hs Facilitates Cytoskeletal Reorganization and Neurite Outgrowth by Localizing the 58-Kd Insulin Receptor Substrate to Filamentous Actin |
| [PMC3190874](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3190874/) | Immunoglobulin E Receptor Signaling and Asthma |
| [PMC2156142](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2156142/) | The Developmental Role of _warthog_, the Notch Modifier Encoding _Drab6_ |
| [PMC2773002](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2773002/) | Differential Role of Human Choline Kinase α and β Enzymes in Lipid Metabolism: Implications in Cancer Onset and Treatment |
| [PMC2196001](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2196001/) | A Novel Neural Wiskott-Aldrich Syndrome Protein (N-Wasp) Binding Protein, Wish, Induces Arp2/3 Complex Activation Independent of Cdc42 |
| [PMC3058384](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3058384/) | COT/MAP3K8 drives resistance to RAF inhibition through MAP kinase pathway reactivation |
| [PMC2063868](https://www.ncbi.nlm.nih.gov/pubmed/16702230) | Semaphorin 4D/Plexin-B1-mediated R-Ras GAP activity inhibits cell migration by regulating beta(1) integrin activity |
| [PMC2064697](https://www.ncbi.nlm.nih.gov/pubmed/17158953) | Loss of linker histone H1 in cellular senescence |
| [PMC4052680](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4052680/) | Phosphorylation by Akt within the ST loop of AMPK-α1 down-regulates its activation in tumour cells |
| [PMC420486](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC420486/)  | Phospholipase C δ-4 overexpression upregulates ErbB1/2 expression, Erk signaling pathway, and proliferation in MCF-7 cells |
| [PMC3135394](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3135394/) | Signal transduction by reactive oxygen species |
| [PMC3378484](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3378484/) | Regulation of lipid binding underlies the activation mechanism of class IA PI3-kinases |
| [PMC3392545](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3392545/) | Structure of STING bound to c-di-GMP Reveals the Mechanism of Cyclic Dinucleotide Recognition by the Immune System |
| [PMC3233644](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3233644/) | A MEK-independent role for CRAF in mitosis and tumor progression |
