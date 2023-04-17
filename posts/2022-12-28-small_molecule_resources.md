---
aliases:
- /chemical-science/machine-learning/resources/2022/12/28/Computational_drug_discovery
categories:
- chemical-science
- machine-learning
- resources
date: '2022-12-28'
description: Compendium of recent articles, resources, and blogs in the area of chemical
  science and drug discovery
layout: post
title: Small Molecules Resources
toc: true

---

Last update: 16th April 2023

## Noteworthy blogs to follow:

1. [Patrick Walters Blog on Cheminformatics](https://practicalcheminformatics.blogspot.com/2021/01/ai-in-drug-discovery-2020-highly.html)
    * [Pat Walter's Cheminformatics Resources list](https://github.com/PatWalters/resources/blob/main/cheminformatics_resources.md)
    
2. [Is Life Worth Living](https://iwatobipen.wordpress.com/)

3. [Andrew White's ML for Molecules and Materials Online Book](https://whitead.github.io/dmol-book/intro.html)

4. [Cheminformia](http://www.cheminformania.com)

5. [Depth-First](https://depth-first.com)

6. [DrugDiscovery.NET - Andreas Bender](http://www.drugdiscovery.net/2019/07/25/new-post1/)

7. [DrugHunter - Dennis Hu](https://drughunter.com)

8. [Practical Fragments](http://practicalfragments.blogspot.com/) 

9. [Derek Lowe's In the Pipeline](https://www.science.org/blogs/pipeline)

## Online resources 

* [Andrea Volkmer, TeachOpenCADD: a teaching platform for computer-aided drug design (CADD)](https://github.com/volkamerlab/TeachOpenCADD) - Highly recommended. 

* [Patrick Walter's Cheminformatics Tutorials](https://github.com/PatWalters/practical_cheminformatics_tutorials)

* [Pat Walters' RSC CICAG Open Source Tools for Chemistry](https://www.macinchem.org/blog/files/fe66130c1da3375e46d0512e483eb901-2791.php?utm_source=pocket_mylist).[Video](https://www.youtube.com/watch?v=2ZjerAGS_IQ). [Github](https://github.com/PatWalters/chem_tutorial)

* [Pen's Python cookbook for Cheminformatics](https://github.com/iwatobipen/py4chemoinformatics)

* [Chem LibreText collection from ACS Division of Chemical Education](https://bit.ly/2SxItoc)

## Books

* [Bajorath, 2011. Chemoinformatics and Computational Chemical Biology. Methods in Molecular Biology.](https://link.springer.com/book/10.1007/978-1-60761-839-3) 

* [Heifetz, Alexander. (Ed.) (2022). "Artificial Intelligence in Drug Design."](https://link.springer.com/book/10.1007/978-1-0716-1787-8)

## Best practices 

* [Bender, Andreas, et al. "Evaluation guidelines for machine learning tools in the chemical sciences." Nature Reviews Chemistry (2022): 1-15.](https://www.nature.com/articles/s41570-022-00391-9). [Temporary SharedIt Link](https://www.nature.com/articles/s41570-022-00391-9.epdf?sharing_token=c7ajAY6RtejsBwo7JKb_EdRgN0jAjWel9jnR3ZoTv0PlqwefS9tuSzOUSTdLlQspcQfdrrg6BP1js7fwhK8sXckoDuc05MIHU8Tf2mCEeVGilKBg5tdIz-htajojgKeP-9SZLLqCDAphBNd8VUtODVWYw0CXTg8CY1uUfyiB8zk%3D)

Nice account outlining guidelines for evaluating different AI/ML methodologies in molecular science. They propose a checklist of tests and best practices to assess the practicality and importance of different methodologies thereby providing a framework on how to evaluate plethora of ML workflows being proposed in different areas of chemical science. The basis for not overlooking the older non-ML method when evaluating the 'new' learning-based method, emphasis on model interpretation to translate the corrleation to chemical causality and finally 

* [Artrith, Nongnuch, et al. "Best practices in machine learning for chemistry." Nature chemistry 13.6 (2021): 505-508.](https://www.nature.com/articles/s41557-021-00716-z)

Set of rules, considerations, and caveats to keep in mind when designing ML model for chemical science. The authors propose a checklist when evaluating ML models, while intuitive at first, when lot of the new ML papers are scanned through that lens, you can identify the shortcommings of the proposed model. This checklist is especially helpful for those entering just entering the field. 


## Reviews

* [F. Strieth-Kalthoff, F. Sandfort, M. H. S. Segler, and F. Glorius, Machine learning the ropes: principles, applications and directions in synthetic chemistry, Chem. Soc. Rev](https://pubs.rsc.org/en/content/articlelanding/2020/CS/C9CS00786E#fn1)

Pedagogical account of various machine learning techniques, models, representation schemes from perspective of synthetic chemistry. Covers different applications of machine learning in synthesis planning, property prediction, molecular design, and reactivity prediction

* [Rodríguez-Pérez, Raquel, Filip Miljković, and Jürgen Bajorath. "Machine Learning in Chemoinformatics and Medicinal Chemistry." Annual review of biomedical data science 5 (2022)](https://www.annualreviews.org/doi/abs/10.1146/annurev-biodatasci-122120-124216)

* [Mariia Matveieva & Pavel Polishchuk. Benchmarks for interpretation of QSAR models](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00519-x). [Github](https://github.com/ci-lab-cz/ibenchmark). [Patrick Walter's blog on the paper](https://patwalters.github.io/practicalcheminformatics/jupyter/ml/interpretability/2021/06/03/interpretable.html).

Paper outlining good practices for interpretating QSAR (Quantative Structure-Property Prediction) models. Good set of heuristics and comparison in the paper in terms of model interpretability. Create 6 synthetic datasets with varying complexity for QSAR tasks. The authors compare interpretability of graph-based methods to conventional QSAR methods. In regards to performance graph-based models show low interpretation compared to conventional QSAR method. 

* [W. Patrick Walters & Regina Barzilay. Applications of Deep Learning in Molecule Generation and Molecular Property Prediction](https://pubs.acs.org/doi/full/10.1021/acs.accounts.0c00699)

Recent review summarising the state of the molecular property prediction and structure generation research. In spite of exciting recent advances in the modeling efforts,  there is a need to generate better (realistic)  training data, assess model prediction confidence, and metrics to quantify molecular generation performance. 

* [Keith, John A., et al. "Combining machine learning and computational chemistry for predictive insights into chemical systems." Chemical reviews 121.16 (2021): 9816-9872.](https://pubs.acs.org/doi/full/10.1021/acs.chemrev.1c00107?utm_source=pcm&utm_medium=twitter&utm_campaign=PUBS_0522_EJK_CR_chreay_CR_Most_Read&src=PUBS_0522_EJK_CR_chreay_CR_Most_Read)

In-depth account of the machine learning and computational methods used in material science and small molecules. Nice introduction to the mathematics and theory behind first-principles based methods. 

* [Navigating through the Maze of Homogeneous Catalyst Design with Machine Learning](https://chemrxiv.org/articles/preprint/Navigating_through_the_Maze_of_Homogeneous_Catalyst_Design_with_Machine_Learning/12786722/1)

* [Coley, C. W. Defining and Exploring Chemical Spaces. Trends in Chemistry 2020](https://doi.org/10.1016/j.trechm.2020.11.004)

* [Applications of Deep learning in molecular generation and molecular property prediction](https://pubs.acs.org/doi/abs/10.1021/acs.accounts.0c00699)

* [Utilising Graph Machine Learning within Drug Discovery and Development](https://arxiv.org/pdf/2012.05716.pdf)

* [Machine learning directed drug formulation development](https://www.sciencedirect.com/science/article/pii/S0169409X21001800?via%3Dihub) 

Review from Aspuru-Guzik and Allen's group discussing how ML can be leveraged for various tasks in drug formulation tasks. 

## Industry-focused drug discovery reviews 

* [Jayatunga, Madura KP, et al. "AI in small-molecule drug discovery: A coming wave." Nat. Rev. Drug Discov 21 (2022): 175-176.](https://www.nature.com/articles/d41573-022-00025-1)

* [Abramov, Yuriy A., Guangxu Sun, and Qun Zeng. "Emerging Landscape of Computational Modeling in Pharmaceutical Development." Journal of Chemical Information and Modeling (2022).](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01580)

Overview of methods and scope of computational methods used in the drug development process. 

* [Dragovich, Peter S., et al. "Small-Molecule Lead-Finding Trends across the Roche and Genentech Research Organizations." Journal of Medicinal Chemistry (2022).](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c02106)

* [A. Bender and I. Cortés-Ciriano, “Artificial intelligence in drug discovery: what is realistic, what are illusions? Part 1: Ways to make an impact, and why we are not there yet,” Drug Discov. Today, vol. 26, no. 2, pp. 511–524, 2021](https://www.sciencedirect.com/science/article/pii/S1359644620305274)

* [A. H. Göller et al., “Bayer’s in silico ADMET platform: a journey of machine learning over the past two decades,” Drug Discov. Today, vol. 25, no. 9, pp. 1702–1709, 2020.](https://www.sciencedirect.com/science/article/pii/S1359644620302609)

* [J. Shen and C. A. Nicolaou, “Molecular property prediction: recent trends in the era of artificial intelligence,” Drug Discov. Today Technol., vol. 32–33, no. xx, pp. 29–36, 2019.](https://www.sciencedirect.com/science/article/abs/pii/S1740674920300032)

* [Mervin, L. H., Johansson, S., Semenova, E., Giblin, K. A., & Engkvist, O. (2021). Uncertainty quantification in drug design. Drug discovery today, 26(2), 474-489.](https://www.sciencedirect.com/science/article/pii/S1359644620305110?via%3Dihub)

* [Congreve, Miles, et al. "Recent developments in fragment-based drug discovery." Journal of medicinal chemistry 51.13 (2008): 3661-3680.](https://pubs.acs.org/doi/10.1021/jm8000373)

## Special Journal Issues

1. [Nice collection of recent papers in Nature Communications on ML application and modeling](https://www.nature.com/collections/gcijejjahe)

2. [Data Science Meets Chemistry](https://pubs.acs.org/page/achre4/data-science-meets-chemistry)

This issue includes contributions that demonstrate the profound impact data science techniques have had in chemistry including chemical and materials synthesis, catalyst and materials design, and overhauling the models used in traditional theoretical or computational chemistry. 

3. [Journal of Medicinal Chemistry compendium of AI in Drug discovery issue](https://pubs.acs.org/doi/full/10.1021/acs.jmedchem.0c01077)

4. [Account of Chemical Research Special Issue on advances in data-driven chemistry research](https://pubs.acs.org/page/achre4/data-science-meets-chemistry)

5. [Special Issue on Reaction Informatics and Chemical Space, Journal of Chemical Information and Modeling (2022)](https://pubs.acs.org/toc/jcisd8/62/9)

## Meeting notes 

* [Warr, W. (2021). National Institutes of Health (NIH) Workshop on Reaction Informatics](https://chemrxiv.org/engage/chemrxiv/article-details/611cf1a6ac8b499b36458d19)

* [Warr, W. (2021). Report on an NIH Workshop on Ultralarge Chemistry Databases.](https://chemrxiv.org/engage/chemrxiv/article-details/60c75883bdbb89984ea3ada5)

## Chemical modalities 

* [Blanco, Maria-Jesus, and Kevin M. Gardinier. "New chemical modalities and strategic thinking in early drug discovery." ACS medicinal chemistry letters 11.3 (2020): 228-231.](https://pubs.acs.org/doi/pdf/10.1021/acsmedchemlett.9b00582)

Overview of different chemical modalities currently at work to address different disease targets. The article addresses the small molecule medicinal chemists and how they can expand their outlook of small molecules to include other molecular entities when considering the angle of attack for different target engagement strategies. The authors offer a nice set of tools and thought process when selecting possible drug modalities for different target classes and what questions should be asked when zeroing in a possible mode of action. 

## Meta themes on optimizing small molecules 

* [Walters, W. Patrick, and Mark A. Murcko. "Prediction of ‘drug-likeness’." Advanced drug delivery reviews 54.3 (2002): 255-271.](https://www.sciencedirect.com/science/article/abs/pii/S0169409X02000030?via%3Dihub) 

* [Veber, Daniel F., et al. "Molecular properties that influence the oral bioavailability of drug candidates." Journal of medicinal chemistry 45.12 (2002): 2615-2623.](https://pubs.acs.org/doi/10.1021/jm020017n)

Retrospective analysis on factors influencing the bioavailability of drug candidates. Authors find rotatable bonds and polar surface area or hydrogen bond count (sum of donor and accpetors) found to be important predictors of good oral bioavailability. Compounds having <10 rotatable bonds and <140 A (or < 12 hydrogen bonds) have good chances of being orally bioavailable. 

* [DeGoey, David A., et al. "Beyond the rule of 5: lessons learned from AbbVie’s drugs and compound collection: miniperspective." Journal of Medicinal Chemistry 61.7 (2017): 2636-2651.](https://pubs.acs.org/doi/10.1021/acs.jmedchem.7b00717)

AB-MPS calculated using cLogD, the number of aromatic rings (nAr), and the number of rotatable bonds (nRotB) according to the formula AB-MPS = Abs(cLogD −3) + nAr + nRotB. The lower the AB-MPS score, the more likely the compound is to be absorbed, and a value of ≤14 is reported to predict a higher probability of oral absorption.

* [Poongavanam, Vasanthanathan, Bradley C. Doak, and Jan Kihlberg. "Opportunities and guidelines for discovery of orally absorbed drugs in beyond rule of 5 space." Current Opinion in Chemical Biology 44 (2018): 23-29.](https://www.sciencedirect.com/science/article/pii/S1367593118300176#bib0030)

Hueristics for oral bioavailability of molecules that are violating the rule of 5. MW may reach up to approximately 1000 Da provided that TPSA increases proportionally up to 250 Å2. In contrast, cLogP and HBDs must be carefully controlled at high MW. Our lack of ability to predict compound conformations and flexibility is currently a hurdle that is critical to overcome to enable further prospective design in oral bRo5 space.

## Synthesis Chemistry 

Catalog of recent research articles that look at synthesis chemistry from a point of view of computational workflows, how traditional synthetic chemistry methods can be combined with informatics to augment drug discovery and synthesis processes. 

* [Ruck, Rebecca T., Neil A. Strotman, and Shane W. Krska. "The Catalysis Laboratory at Merck: 20 Years of Catalyzing Innovation." ACS Catalysis 13 (2022): 475-503.](https://pubs.acs.org/doi/10.1021/acscatal.2c05159#.Y6oIfVMoYEs)

* [Dreher, Spencer D., and Shane W. Krska. "Chemistry informer libraries: Conception, early experience, and role in the future of cheminformatics." Accounts of Chemical Research 54.7 (2021): 1586-1596.](https://pubs.acs.org/doi/10.1021/acs.accounts.0c00760)

Curated set of substrates to quickly assess the practicality of synthetic methods with the complete capture of success and failure, that can optimize reaction conditions with a broader scope with respect to relevant applications.

* [Campos, Kevin R., et al. "The importance of synthetic chemistry in the pharmaceutical industry." Science 363.6424 (2019): eaat0805.](https://www.science.org/doi/pdf/10.1126/science.aat0805)

* [Late-stage diversification of indole skeletons through nitrogen atom insertion](https://www.science.org/doi/10.1126/science.add1383)

* [Lenci, Elena, and Andrea Trabocchi. "Smart Design of Small‐Molecule Libraries: When Organic Synthesis Meets Cheminformatics." ChemBioChem 20.9 (2019): 1115-1123.](https://doi.org/10.1002/cbic.201800751)

## Large chemical libraries 

Over the past few years several entites offering ultra-large ensembles of chemical libraries which can be made on-demand or purchased immediately have emerged. The existence of such services has reinvigorated the field of virtual screening and combinatorial library design. In addition, research groups have devised novel ways to navigate these libraries, more efficiently and also understand the differences in the chemical space these library cover. Following are some of the key papers in the field. 

* [Warr, W. (2021). Report on an NIH Workshop on Ultralarge Chemistry Databases.](https://chemrxiv.org/engage/chemrxiv/article-details/60c75883bdbb89984ea3ada5)

* [Warr, Wendy A., et al. "Exploration of ultralarge compound collections for drug discovery." Journal of Chemical Information and Modeling 62.9 (2022): 2021-2034.](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00224)

* [Bellmann, Louis, et al. "Comparison of combinatorial fragment spaces and its application to ultralarge make-on-demand compound catalogs." Journal of Chemical Information and Modeling 62.3 (2022): 553-566.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.1c01378?casa_token=Lo0YQQrtkcAAAAAA%3AhKiuAJ0GpAhXiNC-2cVO6Ixv0aCnf0J7mrr03mOxpCgH8OpVhaCnDxAkHPNvfm36VsDl8NxvtzusqQ)

SpaceCompare: calculation of the overlap of large, nonenumerable combinatorial fragment spaces, utilizes topological fingerprints and the combinatorial character of these chemical spaces. Enamine’s REAL Space, WuXi’s GalaXi Space, and Otava’s CHEMriya. The overlap of the commercial make-on-demand catalogs is only in the low single-digit percent range, despite their large overall size.

* [Konze, Kyle D., et al. "Reaction-based enumeration, active learning, and free energy calculations to rapidly explore synthetically tractable chemical space and optimize potency of cyclin-dependent kinase 2 inhibitors." Journal of chemical information and modeling 59.9 (2019): 3782-3793.](https://pubs.acs.org/doi/10.1021/acs.jcim.9b00367)

PathFinder uses retrosynthetic analysis followed by combinatorial synthesis to generate novel compounds in synthetically accessible chemical space.


* [Irwin, John J., et al. "ZINC20—a free ultralarge-scale chemical database for ligand discovery." Journal of chemical information and modeling 60.12 (2020): 6065-6073.](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00675)

New version of ZINC with two major new features: billions of new molecules and new methods to search them. As a fully enumerated database, ZINC can be searched precisely using explicit atomic-level graph-based methods. Over 97% of the core Bemis–Murcko scaffolds in make-on-demand libraries are unavailable from “in-stock” collections. Correspondingly, the number of new Bemis–Murcko scaffolds is rising almost as a linear fraction of the elaborated molecules. Thus, an 88-fold increase in the number of molecules in the make-on-demand versus the in-stock sets is built upon a 16-fold increase in the number of Bemis–Murcko scaffolds. The make-on-demand library is also more structurally diverse than physical libraries

* [Neumann, Alexander, Lester Marrison, and Raphael Klein. "Relevance of the Trillion-Sized Chemical Space “eXplore” as a Source for Drug Discovery." ACS Medicinal Chemistry Letters (2023).](https://pubs.acs.org/doi/10.1021/acsmedchemlett.3c00021)

The authors examine the composition of the recently published and, so far, biggest chemical space, “eXplore”, which comprises approximately 2.8 trillion virtual product molecules. The utility of eXplore to retrieve interesting chemistry around approved drugs and common Bemis Murcko scaffolds has been assessed with several methods (FTrees, SpaceLight, SpaceMACS). Further, the overlap between several vendor chemical spaces and a physicochemical property distribution analysis has been performed. Despite the straightforward chemical reactions underlying its setup, eXplore is demonstrated to provide relevant and, most importantly, easily accessible molecules for drug discovery campaigns.

* [Medina, Jorge, and Andrew D. White. "Bloom filters for molecules." arXiv preprint arXiv:2304.05386 (2023).](https://arxiv.org/pdf/2304.05386.pdf)

This paper proposes and studies Bloom filters for testing if a molecule is present in a set using either string or fingerprint representations. Bloom filters are small enough to hold billions of molecules in just a few GB of memory and check membership in sub-milliseconds. The authors found string representations can have a false positive rate below 1% and require significantly less storage than using fingerprints. Canonical SMILES with Bloom filters with the simple FNV hashing function provide fast and accurate membership tests with small memory requirements. They provide a general implementation and specific filters for detecting if a molecule is purchasable, patented, or a natural product according to existing databases at https://github.com/whitead/molbloom.


## Binding free energetic calculations 

* [Xu, Huafeng. "The slow but steady rise of binding free energy calculations in drug discovery." Journal of Computer-Aided Molecular Design (2022): 1-8.](https://link.springer.com/article/10.1007/s10822-022-00494-x)

* [Thompson, James, et al. "Optimizing active learning for free energy calculations." Artificial Intelligence in the Life Sciences 2 (2022): 100050.](https://www.sciencedirect.com/science/article/pii/S2667318522000204)

* [Pitman, Mary, et al. "To Design Scalable Free Energy Perturbation Networks, Optimal Is Not Enough." (2022).](https://chemrxiv.org/engage/chemrxiv/article-details/63894b1f836ceb6cd16f7987)

* [Ganguly, Abir, et al. "AMBER Drug Discovery Boost Tools: Automated Workflow for Production Free-Energy Simulation Setup and Analysis (ProFESSA)." Journal of Chemical Information and Modeling (2022).](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00879)

## Cheminformatics-focus

Catalog of recent reviews and manuscripts I have found useful when learning more about the state-of-the-art in Cheminformatics. I've tried to categorize them roughly based on their area of application: 

### Representation

**Reviews**

* [Representation of Molecules in NN: Molecular representation in AI-driven drug discovery: review and guide](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00460-5)

* [Screening of energetic molecules -- comparing different representations](https://www.nature.com/articles/s41598-018-27344-x)

**Articles** 

* [M. Krenn, F. Hase, A. Nigam, P. Friederich, and A. Aspuru-Guzik, “Self-Referencing Embedded Strings (SELFIES): A 100% robust molecular string representation,” Mach. Learn. Sci. Technol., pp. 1–9, 2020](https://arxiv.org/abs/1905.13741)

* [Could graph neural networks learn better molecular representation for drug discovery? A comparison study of descriptor-based and graph-based models](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00479-8)

Comparative study of descriptor-based and graph-based models using public data set. Used descriptor-based models (XGBoost, RF, SVM, using ECFP) and compared them to graph-based models (GCN, GAT, AttentiveFP, MPNN). They show descriptor-based models outperform the graph-based models in terms of prediction accuracy and computational efficiency with SVM having best predictions. Graph-based methods are good for multi-task learning. 

### Predictive modeling 

* [Fang, Xiaomin, et al. "Geometry-enhanced molecular representation learning for property prediction." Nature Machine Intelligence (2022): 1-8.](https://www.nature.com/articles/s42256-021-00438-4)

Self-supervised learning using special type of GNN architecture (GeoGNN) that includes molecule geometric / spatial information. Geometry-enhanced molecular representation learning method (GEM). The model achieves SOTA performance on 14 of 15 public classification and regression datasets.  

* [Yang, K., Swanson, K., Jin, W., Coley, C., Eiden, P., Gao, H., Guzman-Perez, A., Hopper, T., Kelley, B., Mathea, M. and Palmer, A., 2019. Analyzing learned molecular representations for property prediction. Journal of chemical information and modeling, 59(8), pp.3370-3388](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00237)

Benchmark property prediction models on 19 public and 16 proprietary industrial data sets spanning a wide variety of chemical end points. Introduce a modeling framework (__Chemprop__) that consistently matches or outperforms models using fixed molecular descriptors as well as previous graph neural architectures on both public and proprietary data sets.

* [Stuyver, T. and Coley, C.W., 2021. Quantum chemistry-augmented neural networks for reactivity prediction: Performance, generalizability and interpretability. arXiv preprint arXiv:2107.10402](https://arxiv.org/abs/2107.10402)

Combine structure (Graph-networks) and descriptor based features (QM-derived) to predict activation energies (E<sub>2</sub>/SN<sub>2</sub> barrier height prediction) and regioselectivity. Incorporating QM and structure leads to better overall accuracy and generalizability even in low data regions. Atom and bond level features derived using QM and used in the model generation with a smaller dataset.

### QSAR benchmarks 

* [Exposing the Limitations of Molecular Machine Learning with Activity Cliffs](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01073)

Account on how to treat and analyze activity cliffs in context of developing a predictive model. The authors outline best practices to probe activity cliffs. They show, using 24 DL and ML models and 30 targets, ML approaches based on molecular descriptors outperformed more complex deep learning methods. Activity cliff pairs were defined on similarity of the molecule SMILES and the bioactivity difference.  Compared to most traditional machine learning approaches, deep neural networks seem to fall short at picking up subtle structural differences (and the corresponding property change) that give rise to activity cliffs.

* [MoleculeNet: a benchmark for molecular machine learning (rsc.org)](https://pubs.rsc.org/en/content/articlelanding/2018/sc/c7sc02664a)

* [Large-scale comparison of  machine learning methods for drug target prediction on ChEMBL - Chemical Science (RSC Publishing)](https://pubs.rsc.org/en/content/articlelanding/2018/sc/c8sc00148k)

* [Beyond the hype: deep neural networks outperform established methods using a ChEMBL bioactivity benchmark set, Journal of Cheminformatics](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-017-0232-0)

### Enumeration of chemical space

* [Subbaiah, Murugaiah AM, and Nicholas A. Meanwell. "Bioisosteres of the phenyl ring: Recent strategic applications in lead optimization and drug design." Journal of Medicinal Chemistry 64.19 (2021): 14046-14128.](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c01215)

Looks at biosteric replacements for the phenyl rings in the lead optimization phase. Phenyl rings results in improve potency but have poor solubility and lipophilicitty. Find biosteres can be used to improve them.

* [Ertl, Peter. "Magic Rings: Navigation in the Ring Chemical Space Guided by the Bioactive Rings." Journal of Chemical Information and Modeling (2021).](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00761)

Analyze the nature of rings which appear in bioactive compounds. Ring systems are systematically extracted from one billion molecules and are analyzed to discover a structure or correlation in the bioactivity and type of rings.  No simple set of structural descriptors separating active and inactive rings could be identified, the separation is best described by a neural network model taking into account a complex combination of many substructure features.

* [Bellmann, Louis, et al. "Comparison of Combinatorial Fragment Spaces and Its Application to Ultralarge Make-on-Demand Compound Catalogs." Journal of Chemical Information and Modeling (2022).](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01378)

Authors propose an algorithmic approach called as SpaceCompare to calculate overlap and diversity of the ultra-large combinatorial chemical libraries. The tool uses topological fragment spaces to capture the subtlties of the reaction having same product but different reactant substructures.

* [Zabolotna, Yuliana, et al. "NP navigator: a new look at the natural product chemical space." Molecular informatics 40.9 (2021): 2100068.](https://onlinelibrary.wiley.com/doi/10.1002/minf.202100068).

Organizing the chemical space of ChEMBL, and ZINC to compare its overlap with natural products through COCONUT. Generative Topological Mapping is used for the clustering and analysis. Helpful overview of the method with its application to drug discovery can be found [here](https://www.sciencedirect.com/science/article/pii/S1740674920300044)

* [Nicolaou, Christos A., et al. "The proximal lilly collection: Mapping, exploring and exploiting feasible chemical space." Journal of chemical information and modeling 56.7 (2016): 1253-1266.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.6b00173)

* [Raymond, John W., and Peter Willett. "Maximum common subgraph isomorphism algorithms for the matching of chemical structures." Journal of computer-aided molecular design 16.7 (2002): 521-533.](https://link.springer.com/article/10.1023/A:1021271615909)

* [Dalke, Andrew, Jerome Hert, and Christian Kramer. "mmpdb: An open-source matched molecular pair platform for large multiproperty data sets." Journal of chemical information and modeling 58.5 (2018): 902-910.](https://pubs.acs.org/doi/10.1021/acs.jcim.8b00173)

### Explainable/Interpretable Machine Learning 

**Reviews/Perspectives**

* [Rodríguez-Pérez, Raquel, and Jürgen Bajorath. "Explainable Machine Learning for Property Predictions in Compound Optimization." Journal of medicinal chemistry 64.24 (2021): 17744-17752](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c01789)

**Articles**

* [Wellawatte, Geemi P., Aditi Seshadri, and Andrew D. White. "Model agnostic generation of counterfactual explanations for molecules." (2021).](https://chemrxiv.org/engage/chemrxiv/article-details/613268f0d5f0803706ba0c79)

* [Matveieva, Mariia, and Pavel Polishchuk. "Benchmarks for interpretation of QSAR models." Journal of cheminformatics 13.1 (2021): 1-20](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00519-x). [Patrick Walter's blog](https://patwalters.github.io/practicalcheminformatics/jupyter/ml/interpretability/2021/06/03/interpretable.html)


### Uncertainty quantification

* [Mervin, Lewis H., et al. "Uncertainty quantification in drug design." Drug discovery today 26.2 (2021): 474-489.](https://www.sciencedirect.com/science/article/pii/S1359644620305110)

* [Alan Aspuru-Guzik perspective on uncertainty and confidence](https://arxiv.org/pdf/2102.11439.pdf)

* [Uncertainty Quantification Using Neural Networks for Molecular Property Prediction. J. Chem. Inf. Model. (2020) Hirschfeld, L., Swanson, K., Yang, K., Barzilay, R. & Coley, C. W.](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.0c00502)

Benchmark different models and uncertainty metrics for molecular property prediction. 

* [Evidential Deep learning for guided molecular property prediction and disocovery Ava Soleimany, Conor Coley, et. al.](https://arxiv.org/abs/1910.02600). [Slides](https://slideslive.com/38942396/evidential-deep-learning-for-guided-molecular-property-prediction-and-discovery)

Train network to output the parameters of an evidential distribution. One forward-pass to find the uncertainty as opposed to dropout or ensemble - principled incorporation of uncertainties

* [Differentiable sampling of molecular geometries with uncertainty-based adversarial attacks](https://arxiv.org/pdf/2101.11588.pdf)


* [J. P. Janet, S. Ramesh, C. Duan, H. J. Kulik, ACS Cent. Sci. 2020](https://pubs.acs.org/doi/10.1021/acscentsci.0c00026)

Conduct a global multi-objective optimization with expected improvement criterion. Find transition metal complex redox couples for Redox flow batteries that address stability, solubility, and redox potential metric. Use distance of a point from a training data in latent space as a metric to quantify uncertainty. 

* [J. P. Janet, C. Duan, T. Yang, A. Nandy, H. J. Kulik, Chem. Sci. 2019, 10, 7913–7922](https://pubs.rsc.org/en/content/articlelanding/2019/sc/c9sc02298h#!divAbstract)

Distance from available data in NN latent space is used as a variable for low-cost, quantitative uncertainty metric that works for both inorganic and organic chemistry. Introduce a technique to calibrate latent distances enabling conversion of distance-based metric to error estimates in units of predicted property 


### Active Learning 

Active learning provides strategies for efficient screening of subsets of the library. In many cases, we can identify a large portion of the most promising molecules with a fraction of the compute cost.

* [Reker, D. Practical Considerations for Active Machine Learning in Drug Discovery. Drug Discov. Today Technol. 2020](https://doi.org/10.1016/j.ddtec.2020.06.001)

* [Janet, J. P., Ramesh, S., Duan, C., & Kulik, H. J. (2020). Accurate multiobjective design in a space of millions of transition metal complexes with neural-network-driven efficient global optimization. ACS central science, 6(4), 513-524.](https://pubs.acs.org/doi/abs/10.1021/acscentsci.0c00026)

* [A. P. Soleimany, A. Amini, S. Goldman, D. Rus, S. N. Bhatia, and C. W. Coley, “Evidential Deep Learning for Guided Molecular Property Prediction and Discovery,” ACS Cent. Sci., Jul. 2021.](https://pubs.acs.org/doi/10.1021/acscentsci.1c00546). [Slideshare](https://slideslive.com/38942396/evidential-deep-learning-for-guided-molecular-property-prediction-and-discovery)

Train property prediction model to output a distribution statistics in single pass that describes the uncertainty. This is in contrast to using ensemble models like MC dropout. Interesting way to estimate the epistemic (due to / from model) uncertainty in the prediction. Use this approach on antibiotic search problem of Stokes et. al. Compare Chemprop and SchNet models on different tasks. 

### Transfer Learning  

**Reviews** 

* [Cai, Chenjing, et al. "Transfer learning for drug discovery." Journal of Medicinal Chemistry 63.16 (2020): 8683-8694.](https://pubs.acs.org/doi/pdf/10.1021/acs.jmedchem.9b02147)

**Articles** 

* [Approaching coupled cluster accuracy with a general-purpose neural network potential through transfer learning](https://www.nature.com/articles/s41467-019-10827-4)

Transfer learning by training a network to DFT data and then retrain on a dataset of gold standard QM calculations (CCSD(T)/CBS) that optimally spans chemical space. The resulting potential is broadly applicable to materials science, biology, and chemistry, and billions of times faster than CCSD(T)/CBS calculations.

* [Improving the generative performance of chemical autoencoders through transfer learning](https://iopscience.iop.org/article/10.1088/2632-2153/abae75/meta)

### Meta Learning 

* [Altae-Tran, H., Ramsundar, B., Pappu, A. S., & Pande, V. (2017). Low data drug discovery with one-shot learning. ACS central science, 3(4), 283-293.](https://pubs.acs.org/doi/abs/10.1021/acscentsci.6b00367)

Authors demonstrate how one-shot learning can be used to signifinicantly lower the amount of data required to make predictions in drug discovery tasks. LSTM combined with GCNNs is shown to improve learning capabilities of the model. In the simplest one-shot learning formalism these continuous vectors are then fed into a simple nearest-neighbor classifier that labels new examples by distance-weighted combination of support set labels

* [Nguyen, C. Q., Kreatsoulas, C., & Branson, K. M. (2020). Meta-learning GNN initializations for low-resource molecular property prediction. arXiv preprint arXiv:2003.05996.](https://arxiv.org/pdf/2003.05996.pdf)

Use CheMBL dataset to train a gated graph neural network (GGNN) for prediction and classification tasks using meta learning protocols. Show appreciable model performance even with just approx. 256 datapoints.


### Federated Learning 

* [Simm, Jaak, et al. "Splitting chemical structure data sets for federated privacy-preserving machine learning." Journal of Cheminformatics 13.1 (2021): 1-14.](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00576-2)

* [Melloddy consortium](https://www.melloddy.eu/objectives)

Consortia comprising of leading resarch labs and companies working on decentralized datasets and predictive modeling of biochemical and cellular activity. 

### Generative models

**Reviews** 

* [Comment about generative design from Patrick Walters](https://practicalcheminformatics.blogspot.com/2023/02/generative-molecular-design-we-need-to.html)

* [Walters, W. Patrick, and Mark Murcko. "Assessing the impact of generative AI on medicinal chemistry." Nature biotechnology 38.2 (2020): 143-145.](https://www.nature.com/articles/s41587-020-0418-2)

Correspondence on assessing the impact of AI on medicinal chemistry. It is a well written account on practical implication of generative design on pharmaceutical research.They outline two recent cases of 'success' of AI generative design in drug discovery and give more context and propose best practices for furthering the development of algorithms and drug discovery pipelines. 

* [Mouchlis VD, Afantitis A, Serra A, et al. Advances in de Novo Drug Design: From Conventional to Machine Learning Methods. Int J Mol Sci. 2021;22(4):1676. Published 2021 Feb 7. doi:10.3390/ijms22041676](https://pubmed.ncbi.nlm.nih.gov/33562347/)

* [B. Sanchez-Lengeling and A. Aspuru-Guzik, “Inverse molecular design using machine learning: Generative models for matter engineering,” Science (80)., vol. 361, no. 6400, pp. 360–365, Jul. 2018](https://science.sciencemag.org/content/361/6400/360)

* [Meyers, Joshua, Benedek Fabian, and Nathan Brown. "De novo molecular design and generative models." Drug Discovery Today 26.11 (2021): 2707-2715.](https://www.sciencedirect.com/science/article/pii/S1359644621002531#f0010)

Very nice review of different atom-based, reaction-based, and fragment-based generative design workflows proposed by the community. 

**Benchmarks**

* [Flam-Shepherd, Daniel, Kevin Zhu, and Alán Aspuru-Guzik. "Keeping it Simple: Language Models can learn Complex Molecular Distributions." arXiv preprint arXiv:2112.03041 (2021).](https://arxiv.org/abs/2112.03041). [Nature Comms Link](https://www.nature.com/articles/s41467-022-30839-x)

Test SOTA language models and representation performance against graph-based methods (CGVAE, JTVAE) for 'challenging' generative modeling tasks - generate a molecule - property distribution as a function of synthetic feasiblity. Graph models faced chanllenge in generating large molcules (> 100 HAs). Selfies provided advantage here. All of the models seem to generate novel molecules - how practical each of these novel molecules are is yet an open question. 

* [MOSES - Benchmarking platform for generative models](https://arxiv.org/abs/1811.12823).

Propose a platform to deploy and compare state-of-the-art generative models for exploring molecular space on same dataset. In addition the authors also propose list of metrics  to evaluate the quality and diversity of the generated structures.  

* [GuacaMol: Benchmarking models for De Novo Molecular Design](https://www.benevolent.com/guacamol). [Blogpost](https://www.benevolent.com/research/guacamol-benchmarking-models-for-de-novo-molecular-design)

Evaluation framework from BenevolentAI to compare different de-novo design models. 

* [J. Zhang, R. Mercado, O. Engkvist, and H. Chen, “Comparative Study of Deep Generative Models on Chemical Space Coverage,” J. Chem. Inf. Model., vol. 61, no. 6, pp. 2572–2581, Jun. 2021.](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01328)

Interesting analysis from team at AstraZeneca R&D. They look at the chemical space coverage accounted by the SOTA generative models. Proposes a metric for evaluating space coverage, and thereby comparing different SOTA models, using a reference data (GDB-13 in this case). The new metric computes how much of the GDB-13 dataset can be recovered by a model that is trained on small GDB subset.  Generative models were trained on same 1M data points and 1B molecules were then sampled from each model. It was seen that at most 39% of the molecules in the parent dataset were sampled / generated by the model. Most models sampled the same compounds atleast twice. It was observed that graph-based model sampled much diverse molecules than string-based methods. Besides, the coverage of GAN-based models was worse compared to Language and Graph models. 

* [Gao, W.; Coley, C. W. The Synthesizability of Molecules Proposed by Generative Models. J. Chem. Inf. Model. 2020](https://doi.org/10.1021/acs.jcim.0c00174)

This paper looks at different ways of integrating synthesizability criteria into generative models. 

* [Comparative analysis of graph traversal schemes for GraphINVENT](https://chemrxiv.org/engage/chemrxiv/article-details/614757fa6fc3a870f6a4bbe2)

Bechmark work from AstraZeneca/MIT AI team to document different graph architecture schemes and algorithms for generative models. 


**Language models:**

* [R. Gómez-Bombarelli et al., “Automatic Chemical Design Using a Data-Driven Continuous Representation of Molecules,” ACS Cent. Sci., vol. 4, no. 2, pp. 268–276, 2018](https://pubs.acs.org/doi/10.1021/acscentsci.7b00572)

One of the first implementation of a variation auto-encoder for molecule generation

* [Penalized Variational Autoencoder](https://s3-eu-west-1.amazonaws.com/itempdf74155353254prod/7977131/Penalized_Variational_Autoencoder_for_Molecular_Design_v2.pdf)

* [SELFIES and generative models using STONED](https://chemrxiv.org/articles/preprint/Beyond_Generative_Models_Superfast_Traversal_Optimization_Novelty_Exploration_and_Discovery_STONED_Algorithm_for_Molecules_using_SELFIES/13383266) 

Representation using SELFIES proposed to make it much more powerful

* [Reproducibility study of the STONED work from Jablonka et. al.](https://arxiv.org/pdf/2102.00700.pdf)

* [LSTM based (RNN) approaches to small molecule generation](https://s3-eu-west-1.amazonaws.com/itempdf74155353254prod/10119299/Generating_Customized_Compound_Libraries_for_Drug_Discovery_with_Machine_Intelligence_v1.pdf). [Github](https://github.com/ETHmodlab/BIMODAL)

* [Chithrananda, S.; Grand, G.; Ramsundar, B. ChemBERTa: Large-Scale Self-Supervised Pretraining for Molecular Property Prediction. arXiv [cs.LG], 2020](https://arxiv.org/abs/2010.09885).

* [SMILES-based deep generative scaffold decorator for de-novo drug design](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00441-8#availability-of-data-and-materials). [Github](https://github.com/undeadpixel/reinvent-randomized)

SMILES-based language model that generates molecules from scaffolds and can be trained from any arbitrary molecular set. Uses randomized SMILES to improve final prediction validity. 

* [Iovanac, Nicolae C., Robert MacKnight, and Brett Savoie. "Actively Searching: Inverse Design of Novel Molecules with Simultaneously Optimized Properties." ChemRxiv (2021)](https://chemrxiv.org/engage/chemrxiv/article-details/60c7591a9abda2847ff8ea1f)

Using quantum chemistry attributes calculated on-the-fly as scoring functions for sampling the generative model chemical space. Active learning strategy is deployed to explore the area of space where the properties of the molecules are unknown. 

**Graph-based**

* [Flam-Shepherd, Daniel, Alexander Zhigalin, and Alán Aspuru-Guzik. "Scalable Fragment-Based 3D Molecular Design with Reinforcement Learning." arXiv preprint arXiv:2202.00658 (2022)](https://arxiv.org/abs/2202.00658?)

Reinforcement learning-based generative model whici is an update on point cloud approach by the same group to now incorporate 'grammar' for building molecules in form of functional groups in 3D space. 

* [W. Jin, R. Barzilay, and T. Jaakkola, “Junction tree variational autoencoder for molecular graph generation,” 35th Int. Conf. Mach. Learn. ICML 2018, vol. 5, pp. 3632–3648, 2018](https://arxiv.org/abs/1802.04364)

Junction tree based decoding. Define a grammar for the small molecule and find sub-units based on that grammar to construct a molecule. The molecule is generated in two-steps: first being generating the scaffold or backbone of the molelcule, then the nodes  are added with molecular substructure as identified from the 'molecular grammar'. 

* [MPGVAE: Message passing graph networks for molecular generation, Daniel Flam-Shepherd et al 2021 Mach. Learn.: Sci. Technol.](https://iopscience.iop.org/article/10.1088/2632-2153/abf5b7/pdf)

Introduce a graph generation model by building a Message Passing Neural Network (MPNNs) into the encoder and decoder of a VAE (MPGVAE).

* [ConfVAE: End-to-end framework for molecular conformation generation via bilevel programming](https://arxiv.org/pdf/2105.07246.pdf)

Algorithm to predict 3D conforms from molecular graphs.

* [GraphINVENT: R. Mercado, T. Rastemo, E. Lindelöf, G. Klambauer and O. Engkvist, “Graph networks for molecular design,” Mach. Learn. Sci. Technol., vol. 2, no. 2, p. 25023, 2021](https://iopscience.iop.org/article/10.1088/2632-2153/abcf91/meta). [Github](https://github.com/MolecularAI/GraphINVENT). [Blogpost](https://www.cheminformania.com/using-graphinvent-to-generate-novel-drd2-actives/)

GraphINVENT uses a tiered deep neural network architecture to probabilistically generate new molecules a single bond at a time. 

* [RL-GraphINVENT: Reinforcement learning-based variant of the above code.](https://chemrxiv.org/engage/chemrxiv/article-details/60fc07bd171fc7a0adb87039)


**GANs**

* [MolGAN: An implicit generative model for small molecular graphs, N. De Cao and T. Kipf, 2018](https://arxiv.org/abs/1805.11973)

Generative adversarial network for finding small molecules using graph networks, quite interesting. Avoids issues arising from node ordering that are associated with likelihood based methods by using an adversarial loss instead (GAN)

* [LatentGAN: A de novo molecular generation method using latent vector based generative adversarial network](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-019-0397-9)

Molecular generation strategy is described which combines an autoencoder and a GAN. Generator and discriminator network do not use SMILES strings as input, but instead n-dimensional vectors derived from the code-layer of an autoencoder trained as a SMILES heteroencoder that way syntax issues are expected to be addressed. 

**Scaffold-retained** 

* [Kaitoh, Kazuma, and Yoshihiro Yamanishi. "Scaffold-Retained Structure Generator to Exhaustively Create Molecules in an Arbitrary Chemical Space." Journal of Chemical Information and Modeling (2022).](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01130)

* [Maziarz, Krzysztof, et al. "Learning to extend molecular scaffolds with structural motifs." arXiv preprint arXiv:2103.03864 (2021).](https://arxiv.org/pdf/2103.03864.pdf)

Team at Novartis and Microsoft propose MoLeR, graph based model to generate molecule using scaffold as a seed. Scaffold based SAR speed up shown. 

**Reaction tranformation-based** 

Here the idea is to constraint the molecules generated by the transformations amenable to a particular platform, like automated synthesis workflow. 

* [Seo, Seonghwan, Jaechang Lim, and Woo Youn Kim. "Molecular Generative Model via Retrosynthetically Prepared Chemical Building Block Assembly." Advanced Science (2023): 2206674.](https://onlinelibrary.wiley.com/doi/10.1002/advs.202206674?utm_source=pocket_saves)

* [Bradshaw, John, et al. "Barking up the right tree: an approach to search over molecule synthesis dags." Advances in neural information processing systems 33 (2020): 6852-6866.](https://arxiv.org/pdf/2012.11522.pdf)

* [Fialková, Vendy, et al. "LibINVENT: reaction-based generative scaffold decoration for in silico library design." Journal of Chemical Information and Modeling 62.9 (2021): 2046-2063.](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00469)

* [Nguyen, Dai Hai, and Koji Tsuda. "A generative model for molecule generation based on chemical reaction trees." arXiv preprint arXiv:2106.03394 (2021).](https://arxiv.org/pdf/2106.03394.pdf)

Authors propose a generative model to generate molecules via multi-step chemical reaction trees, each campaign first generates a reaction-tree with template transformations as breaking points.

* [Bradshaw, John, et al. "A model to search for synthesizable molecules." Advances in Neural Information Processing Systems 32 (2019).](https://arxiv.org/abs/1906.05221)

**3D conformations-aware** 

* [Bolcato, Giovanni, Esther Heid, and Jonas Boström. "On the Value of Using 3D Shape and Electrostatic Similarities in Deep Generative Methods." Journal of chemical information and modeling 62.6 (2022): 1388-1398.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.1c01535)

Extension to the fragment-based generative design model (DeepFMPO) using reinforcement learning now incorporating 3D electrostatic similarity in the analysis. Ability to replace fragment with similar 3D shape and electrostatics. ESP_sim [tutorial](https://www.youtube.com/watch?v=Ka08REoGYvI) for comparison of electrostatic potential and molecule shape is used for this purpose. The authors find scaffold-hopping bioisoteres for CDK2. 

* [Imrie, Fergus, et al. "Deep generative design with 3D pharmacophoric constraints." Chemical science 12.43 (2021): 14577-14589.](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc02436a#!)

Method that combines GNNs with CNNs to incorporate 3D pharmacophoric constraints into molecular generation. 

* [Imrie, Fergus, et al. "Deep generative models for 3D linker design." Journal of chemical information and modeling 60.4 (2020): 1983-1995.](https://pubs.acs.org/doi/10.1021/acs.jcim.9b01120 )

Interesting work on designing linkers using conformation aware generative design algorithm. Think of it like fragment-growing. 

**Protein-ligand interactions aware** 

* [Zhang, Jie, and Hongming Chen. "De novo molecule design using molecular generative models constrained by ligand–protein interactions." Journal of Chemical Information and Modeling 62.14 (2022): 3291-3306.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.2c00177)


**Linker design**

* [Igashov, Ilia, et al. "Equivariant 3d-conditional diffusion models for molecular linker design." arXiv preprint arXiv:2210.05274 (2022).](https://arxiv.org/abs/2210.05274)

* [Guo, Jeff, et al. "Link-INVENT: Generative Linker Design with Reinforcement Learning." (2022).](https://chemrxiv.org/engage/chemrxiv/article-details/62628b2debac3a61c7debf31). [BlogPost](https://iwatobipen.wordpress.com/2022/06/04/generate-molecules-with-link-invent-rdkit-rinvent-chemoinformatics/)

* [Imrie, Fergus, et al. "Deep generative models for 3D linker design." Journal of chemical information and modeling 60.4 (2020): 1983-1995.](https://pubs.acs.org/doi/10.1021/acs.jcim.9b01120). [Blogpost](https://iwatobipen.wordpress.com/2020/05/09/replace-core-with-delinker-rdkit-chemoinformatics-deeplearning/)

* [Nori, Divya, Connor W. Coley, and Rocío Mercado. "De novo PROTAC design using graph-based deep generative models." arXiv preprint arXiv:2211.02660 (2022).](https://arxiv.org/abs/2211.02660)

### Computer Aided Synthesis Planning (CASP) 

**Reviews:** 

* [Thakkar, Amol, et al. "Artificial intelligence and automation in computer aided synthesis planning." Reaction chemistry & engineering 6.1 (2021): 27-51.](https://pubs.rsc.org/en/content/articlehtml/2021/xx/d0re00340a?casa_token=XlT3Q35wF_QAAAAA:Rcge3W9WUQher8k9zVMPBUQJsCeOskpUZOvQShiCcVZw127BHRFMRrZL0X6Upa9eHD-KMYPBNTaPww)

Perspective on the current SOTA of synthesis planning, automation, and reaction optimization in drug discovery and development phases using AI and ML. 

* [Madzhidov, T. I., et al. (2021). "Machine learning modelling of chemical reaction characteristics: yesterday, today, tomorrow." Mendeleev Communications 31(6): 769-780.](https://www.sciencedirect.com/science/article/abs/pii/S0959943621002959?dgcid=author)

* [Jorner, K., et al. (2021). "Organic reactivity from mechanism to machine learning." Nature Reviews Chemistry 5(4): 240-255.](https://www.nature.com/articles/s41570-021-00260-x)

* [Struble, T. J., et al. (2020). "Current and Future Roles of Artificial Intelligence in Medicinal Chemistry Synthesis." J Med Chem 63(16): 8667-8682](https://pubs.acs.org/doi/pdf/10.1021/acs.jmedchem.9b02120)

* [Zuranski, Andrzej M., et al. "Predicting reaction yields via supervised learning." Accounts of chemical research 54.8 (2021): 1856-1865.](https://pubs.acs.org/doi/full/10.1021/acs.accounts.0c00770)

Perspective on ML for organic chemistry reactivity prediction. Group uses DFT-derived physical features of the reaction molecules and conditions for representation. Small data set plus HTE experimentation dataset for yield estimation. 

* [The Exploration of Chemical Reaction Networks](https://arxiv.org/pdf/1906.10223.pdf)

Perspective article summarising their position on the current state of research and future considerations on developing better reaction network models. Break down the analysis of reaction networks as into 3 classes (1) Front Open End: exploration of products from reactants (2) Backward Open Start: Know the product and explore potential reactants (3) Start to End: Product and reactant known, explore the likely intermediates. 

Nice summary of potential challenges in the field:

- Validating exploration algorithms on a consistent set of reaction system. 
- Need to generate a comparative metric to benchmark different algorithms.  
- Considering effect of solvents and/or protein embeddings in the analysis

    * Previous review article by same group: [Exploration of Reaction Pathways and Chemical Transformation Networks](https://pubs.acs.org/doi/pdf/10.1021/acs.jpca.8b10007)

Technical details of various algorithms being implemented for reaction mechanism discovery at the time of writing the review. 


**Best practices** 

* [Gimadiev, T. R., Lin, A., Afonina, V. A., Batyrshin, D., Nugmanov, R. I., Akhmetshin, T., ... & Varnek, A. (2021). Reaction Data Curation I: Chemical Structures and Transformations Standardization. Molecular Informatics, 2100119.](https://onlinelibrary.wiley.com/doi/abs/10.1002/minf.202100119?casa_token=SczoexCIDDUAAAAA:3M-uhrRFMaNRnydOQb-NBhJ1VvocjwZ1_ll--OGP1QwJ-X5Amwt24M586NXxbbgazYn0t-NBAmxS1oFk)

Article from Varnek group on best practices on processing data for reaction informatics. 


**Benchmarking**

* [Genheden S, Bjerrum E. PaRoutes: a framework for benchmarking retrosynthesis route predictions. ChemRxiv. Cambridge: Cambridge Open Engage; 2022](https://chemrxiv.org/engage/chemrxiv/article-details/621c86f3c3e9da4f737b0047). [Github](https://github.com/MolecularAI/PaRoutes)

Benchmarking framework for comparing different multi-step retrosynthesis methods from researchers at AstraZeneca R&D. Provides 10k synthetic routes which can be used as a validation set for different methodologies, providing a platform for systematic comparison of different methods being proposed in the community. 


**Classifying chemical reactions:**

* [Schneider, N., et al. (2015). "Development of a Novel Fingerprint for Chemical Reactions and Its Application to Large-Scale Reaction Classification and Similarity." Journal of Chemical Information and Modeling 55(1): 39-53.](https://pubs.acs.org/doi/10.1021/ci5006614)

Using scrapped US Patent data to classify chemical reactions and deploy various fingerprints and ML models for classification. 

* [Schwaller, Philippe, et al. "Mapping the space of chemical reactions using attention-based neural networks." Nature Machine Intelligence 3.2 (2021): 144-152.](https://www.nature.com/articles/s42256-020-00284-w). [rxnfp - Github](https://github.com/rxn4chemistry/rxnfp). [Preprint](https://arxiv.org/abs/2012.06051). [News Article](https://cen.acs.org/physical-chemistry/computational-chemistry/Mapping-reaction-space-machine-learning/99/i5?utm_source=LatestNews&utm_medium=LatestNews&utm_campaign=CENRSS). 

Transformer-based model for reaction classification. Compared it with BERT. Besides classification, the work also formalizes the reaction fingerprint generation using the learned representations. The reaction fingerprints are visualized using TMAPS.  

* [Probst, Daniel, Philippe Schwaller, and Jean-Louis Reymond. "Reaction Classification and Yield Prediction Using the Differential Reaction Fingerprint DRFP." ChemRxiv (2021)](https://chemrxiv.org/engage/chemrxiv/article-details/60e358fb379e8d3ba9f92d15)

* [Delannée, V., Nicklaus, M.C. ReactionCode: format for reaction searching, analysis, classification, transform, and encoding/decoding. J Cheminform 12, 72 (2020)](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00476-x)

* [Heid, E; Green, W; Machine learning of reaction properties via learned representations of the condensed graph of reaction. ChemRxiv (2021)](https://chemrxiv.org/engage/chemrxiv/article-details/6112ac487117507542e68bef)

Reaction classifiction prediction using atom-mapped reaction that are used to generate condensed reaction graphs and passed through a GCN-variant as implemented in chemprop. 

**Atom mapping:** 

* [Lin, A., et al. (2021). "Atom-to-atom Mapping: A Benchmarking Study of Popular Mapping Algorithms and Consensus Strategies."](https://onlinelibrary.wiley.com/doi/10.1002/minf.202100138?af=R)

Comparative analysis of different atom-mapping schemes for generating atom-mapped reaction features. Comments on the state of the art methods and their performance on a curated reaction database. 

* [Extraction of organic chemistry grammar from unsupervised learning of chemical reactions](https://advances.sciencemag.org/content/7/15/eabe4166). [RXMapper](https://github.com/rxn4chemistry/rxnmapper)

Data-driven atom mapping schemes which uses transformers for learning the context of the chemical reaction. Researchers at IBM trained a flavor of language model based on Transformer architecture and used it to find reaction centers and maps atoms. Shown to be robust compared to other SOTA methods. 

* [Automatic mapping of atoms across both simple and complex chemical reactions](https://www.nature.com/articles/s41467-019-09440-2)

**Predicting reaction outcomes:** 

* [Jin, Wengong, et al. "Predicting organic reaction outcomes with weisfeiler-lehman network." Advances in neural information processing systems 30 (2017).](https://arxiv.org/abs/1709.04555)

* [C. W. Coley et al., “A graph-convolutional neural network model for the prediction of chemical reactivity,” Chem. Sci., vol. 10, no. 2, pp. 370–377, 2019.](https://pubs.rsc.org/en/content/articlepdf/2019/sc/c8sc04228d)

Template-free prediction of organic reaction outcomes using graph convolutional neural networks

* [Prediction of Organic Reaction Outcomes Using Machine Learning, ACS Cent. Sci. 2017](https://pubs.acs.org/doi/10.1021/acscentsci.7b00064?ref=acsciiVIdeepchemistry)

* [Guan, Y., et al. (2021). "Regio-selectivity prediction with a machine-learned reaction representation and on-the-fly quantum mechanical descriptors." Chemical Science 12(6): 2198-2208](https://pubs.rsc.org/en/content/articlehtml/2021/sc/d0sc04823b)

* [Schwaller, P., et al. (2019). "Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction." ACS Central Science 5(9): 1572-1583.](https://pubs.acs.org/doi/10.1021/acscentsci.9b00576) 

* [Schwaller, P., et al. (2021). "Prediction of chemical reaction yields using deep learning." Machine Learning: Science and Technology 2(1)](https://iopscience.iop.org/article/10.1088/2632-2153/abc81d)

**Retrosynthetic routes:** 

* [Zabolotna, Y., et al. (2021). "SynthI: A New Open-Source Tool for Synthon-Based Library Design." Journal of Chemical Information and Modeling.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.1c00754)

Interesting work on de-novo design of molecules wherein, the molecules being created are made up from the fragments that is known to exist and are available to the user. New molecules are generated based on the fragmented (synthons) made available in the dataset. 

* [Schwaller, P., et al. (2020). "Predicting retrosynthetic pathways using transformer-based models and a hyper-graph exploration strategy." Chemical Science 11(12): 3316-3325.](https://pubs.rsc.org/en/content/articlelanding/2020/sc/c9sc05704h)

* [Computational planning of the synthesis of complex natural products](https://www.nature.com/articles/s41586-020-2855-y)

* [Watson, I. A., et al. (2019). "A retrosynthetic analysis algorithm implementation." J Cheminform 11(1)](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0323-6)

* [Segler, Marwin HS, and Mark P. Waller. "Neural‐symbolic machine learning for retrosynthesis and reaction prediction." Chemistry–A European Journal 23.25 (2017): 5966-5971.](https://chemistry-europe.onlinelibrary.wiley.com/doi/10.1002/chem.201605499)

Hybrid neural-symbolic approach for both retrosynthesis and reaction prediction that can be trained with large reaction sets from databases. Template extraction from known reaction datasets to classify new reaction to known reaction classes. 

* [Fortunato, Michael E., et al. "Data augmentation and pretraining for template-based retrosynthetic prediction in computer-aided synthesis planning." Journal of chemical information and modeling 60.7 (2020): 3398-3407.](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00403)

In template-based retrosynthesis predictions, templates with few examples are excluded from training. This works talks on methods to augment the current set of data to account for the cases where examples for training are few. 

* [Seidl, Philipp, et al. "Improving Few-and Zero-Shot Reaction Template Prediction Using Modern Hopfield Networks." Journal of chemical information and modeling 62.9 (2022): 2111-2120.](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01065)

Introduce a template-based single-step retrosynthesis model based on Modern Hopfield
Networks, which learn an encoding of both molecules and reaction templates in order to
predict the relevance of templates for a given molecule. The model does not consider templates as distinct categories, but can leverage structural information about the template. The retrieval approach enables generalization across templates, which makes zero-shot learning possible and improves few-shot learning. On the single-step retrosynthesis benchmark USPTO-50k, the MHN model reaction reaches the state-of-the-art at top-k accuracy for k ≥ 3. 

* [Tu, Zhengkai, and Connor W. Coley. "Permutation invariant graph-to-sequence model for template-free retrosynthesis and reaction prediction." Journal of Chemical Information and Modeling (2021).](https://pubs.acs.org/doi/full/10.1021/acs.jcim.2c00321)

Graph2SMILES, a template-free retrosynthesis model to predict reaction outcomes and retrosynthesis routes. This model eliminates the need for any input-side SMILES augmentation, while achieving noticeable improvements over Transformer baselines (especially for top-1 accuracy). 

**Generate reaction networks:**

* [M. Liu et al., “Reaction Mechanism Generator v3.0: Advances in Automatic Mechanism Generation,” J. Chem. Inf. Model., May 2021](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01480)

Newest version of RMG (v3) is updated to Python v3. It has ability to generate heterogeneous catalyst models, uncertainty analysis to conduct first order sensitivity analysis. RMG dataset for the thermochemical and kinetic parameters have been expanded. 

* [More and Faster: Simultaneously Improving Reaction Coverage and Computational Cost in Automated Reaction Prediction Tasks](https://s3-eu-west-1.amazonaws.com/itempdf74155353254prod/13076087/More_and_Faster__Simultaneously_Improving_Reaction_Coverage_and_Computational_Cost_in_Automated_Reaction_Prediction_Task_v1.pdf)

Presents an algorithmic improvement to the reaction network prediction task through their YARP (Yet Another Reaction Program) methodology. Shown to reduce computational cost of optimization while improving the diversity of identified products and reaction pathways. 

* [Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction](https://pubs.acs.org/doi/abs/10.1021/acscentsci.9b00576)
    * Follow-up: [Quantitative interpretation explains machine learning models for chemical reaction prediction and uncovers bias](https://www.nature.com/articles/s41467-021-21895-w)

* [Automatic discovery of chemical reactions using imposed activation](https://chemrxiv.org/articles/preprint/Automatic_discovery_of_chemical_reactions_using_imposed_activation/13008500/1)

* [Machine learning in chemical reaction space](https://www.nature.com/articles/s41467-020-19267-x)

Look at exploration of reaction space rather than compound space. SOAP kernel for representing the moelcules. Estimate atomization energy for the molecules using ML. Calculate the d(AE) for different ML-estimated AEs. Reaction energies (RE) are estimated and uncertainty propogation is used to estimate the errors. Uncorrelated constant error propogation. 30,000 bond breaking reaction steps Rad-6-RE network used. RE prediction is not as good as AE. 


**Estimate molecular synthesizability**

The idea of estimating whether a molecule is 'synthesizable' can be thought of from two areas:
1. Complexity based - compare the fragments in the molecule to the known fragments in the chemical space  
2. Full retrosynthesis based - entire route is considered for molecule generation. Reactant complexity drives route complexity. 

* [Ertl, Peter, and Ansgar Schuffenhauer. "Estimation of synthetic accessibility score of drug-like molecules based on molecular complexity and fragment contributions." Journal of cheminformatics 1.1 (2009): 1-11.](https://jcheminf.biomedcentral.com/articles/10.1186/1758-2946-1-8). [RDkit implementation](https://github.com/rdkit/rdkit/tree/master/Contrib/SA_Score)

Synthetic Accessbility  score (SA_Score) is a popular heuristic score for quantifying synthesizability. It computes a score using a fragment-contribution approach, where rarer fragments (as judged by their abundance in the PubChem database of 1mil representative cmpds) are taken as an indication of lower synthesizability. 


* [Coley, Connor W., et al. "SCScore: synthetic complexity learned from a reaction corpus." Journal of chemical information and modeling 58.2 (2018): 252-261.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.7b00622). [DeepChem implementation](https://github.com/deepchem/deepchem/blob/master/examples/tutorials/Synthetic_Feasibility_Scoring.ipynb)

SCScore is a learned synthetic complexity score computed as a neural network model trained on reaction data from the Reaxys database. It was designed with synthesis planning in mind to operate on molecules resembling not just drug-like products but intermediates and simpler building blocks as well.

* [Liu, Cheng-Hao, et al. "RetroGNN: Fast Estimation of Synthesizability for Virtual Screening and De Novo Design by Learning from Slow Retrosynthesis Software." Journal of Chemical Information and Modeling 62.10 (2022): 2293-2300.](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01476)

RetroGNN is a graph neural network based model to predict outcome of a synthesis planner given the target molecule. Shown to better perform than SAScore. Code is yet to be released. 

### Data-driven chemistry modeling and reaction optimization

**Review**

* [Williams, Wendy L., et al. "The evolution of data-driven modeling in organic chemistry." ACS central science 7.10 (2021): 1622-1637.](https://pubs.acs.org/doi/full/10.1021/acscentsci.1c00535)


**Articles**

* [B. J. Shields et al., “Bayesian reaction optimization as a tool for chemical synthesis,” Nature, vol. 590, no. June 2020, p. 89, 2021](https://www.nature.com/articles/s41586-021-03213-y). [Github](https://github.com/b-shields/edbo)

Experimental design using Bayesian Optimization. Look at 3 rxn class with multiple reaction parameters - temp solvent ligand. Algorithm identifies the optimal conditions. Variables looked into: ligands, bases, solvents, temperatures, concentrations. Algorithm arrived at 99% yields consistently - which was possible by using unusual ligand not known to work well (cognitive bias).

* [Torres, Jose Garrido, et al. "A Multi-Objective Active Learning Platform and Web App for Reaction Optimization." (2022).](https://chemrxiv.org/engage/chemrxiv/article-details/62f6966269f3a5df46b5584b)

* [Hickman, Riley J., et al. "Bayesian optimization with known experimental and design constraints for chemistry applications." arXiv preprint arXiv:2203.17241 (2022).](https://arxiv.org/abs/2203.17241)

* [Häse, Florian, et al. "Gryffin: An algorithm for Bayesian optimization of categorical variables informed by expert knowledge." Applied Physics Reviews 8.3 (2021): 031406.](https://aip.scitation.org/doi/abs/10.1063/5.0048164)

* [Dotson, Jordan, et al. "Data-driven multi-objective optimization tactics for catalytic asymmetric reactions." (2022).](https://chemrxiv.org/engage/chemrxiv/article-details/62b2dc4b7da6ce2ddb1b3264)

Multi-objective optimization of catalytic reactions that employ chiral bisphosphine ligands. Optimization of 2 sequential reactions in asymmetric synthesis of API. Classification method identify active catalysts -- 5% yield (user provided) cutoff for binary classification. Linear regression to model reaction selectivity. DFT-derived descriptor dataset of >550 bisphosphine ligands. Develop an interpretable chemical space mapping tool using PCA. Look at the domain of applicability with the euclidean distance in chemical space. 

* [Zhang, Ying, et al. "Descriptor-Free Design of Multicomponent Catalysts." ACS Catalysis 12 (2022): 10562-10571.](https://pubs.acs.org/doi/10.1021/acscatal.2c02807#.YvpbIMo0Ovw.linkedin)

Bayesian optimization (BO) to improve the experimental measured activity as a direct function of compositional variables without educating physical knowledge to the machine. We applied BO in screening spinel Cr<sub>a</sub>Mn<sub>b</sub>Fe<sub>c</sub>Co<sub>d</sub>Ni<sub>e</sub>Cu<sub>f</sub>Zn<sub>3–a–b–c–d–e–f</sub>O<sub>4</sub> for the decomposition of nitric oxide into environmentally friendly nitrogen.

**Databases**

* [Kearnes, S. M., et al. (2021). "The Open Reaction Database." Journal of the American Chemical Society.](https://pubs.acs.org/doi/full/10.1021/jacs.1c09820?utm_source=pocket_mylist)

* [Rohrbach, Simon, et al. "Digitization and validation of a chemical synthesis literature database in the ChemPU." Science 377.6602 (2022): 172-180.](https://www.science.org/doi/10.1126/science.abo0058)

### Automated chemistry workflows 

* [Seifrid, Martin, et al. "Autonomous Chemical Experiments: Challenges and Perspectives on Establishing a Self-Driving Lab." Accounts of Chemical Research (2022): e0229862-131.](https://pubs.acs.org/doi/abs/10.1021/acs.accounts.2c00220)

* [Nambiar, Anirudh MK, et al. "Bayesian Optimization of Computer-Proposed Multistep Synthetic Routes on an Automated Robotic Flow Platform." ACS Central Science (2022).](https://pubs.acs.org/doi/10.1021/acscentsci.2c00207)

* [Wilbraham, Liam, S. Hessam M. Mehr, and Leroy Cronin. "Digitizing chemistry using the chemical processing unit: from synthesis to discovery." Accounts of Chemical Research 54.2 (2020): 253-262.](https://pubs.acs.org/doi/full/10.1021/acs.accounts.0c00674)


* [Godfrey, Alexander G., Thierry Masquelin, and Horst Hemmerle. "A remote-controlled adaptive medchem lab: an innovative approach to enable drug discovery in the 21st Century." Drug Discovery Today 18.17-18 (2013): 795-802.](https://www.sciencedirect.com/science/article/pii/S135964461300069X)

Account of Eli Lilly and Company's ASL (Automated Synthesis Lab)

### DNA-encoded Libraries 

* [Matthew Clark, et. al. DNA-encoded small-molecule libraries (DEL)](https://www.nature.com/articles/nchembio.211). [C&EN article on the topic](https://cen.acs.org/articles/95/i25/DNA-encoded-libraries-revolutionizing-drug.html)

New form of storing huge amounts of molecule related data using DNA. Made partially possible by low cost of DNA sequencing. Each molecule in the storage is attached with a DNA strand which encode information about its recipe. 

- [Follow up to the work with Machine Learning for hit finding.](https://pubs.acs.org/doi/abs/10.1021/acs.jmedchem.0c00452)
 
DNA encodings for discovery of novel small-molecule protein inhibitors. Outline a process for building a ML model using DEL. Compare graph convolutions to random forest for classification tasks with application to protein target binding. Graph models seemed to achieve high hit rate comapred to random forest. Apply diversity, logistical, structural filtering to search for novel candidates. First work to use GCN for hit searching.

* [Martín, A., et al. (2020). "Navigating the DNA encoded libraries chemical space." Communications Chemistry 3(1).](https://www.nature.com/articles/s42004-020-00374-1?error=cookies_not_supported&code=2d1394f8-2e1b-46ef-b926-9441292aea56)

* [Zabolotna, Y., Pikalyova, R., Volochnyuk, D., Horvath, D., Marcou, G., & Varnek, A. (2021). Exploration of the chemical space of DNA-encoded libraries.](https://chemrxiv.org/engage/chemrxiv/article-details/60fac8718804431689e3155b)

## Code / Packages:

* [Molecular AI department at AstraZeneca R&D](https://github.com/MolecularAI)

* [Jazzy: Fast calculation of hydrogen-bond strengths and free energy of hydration of small molecules](https://www.nature.com/articles/s41598-023-30089-x)

* [GHOST: Generalized threshold shifting procedure](https://github.com/rinikerlab/GHOST). [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00160). [Blogpost](https://greglandrum.github.io/rdkit-blog/exploratory/machinelearning/2021/12/23/ternary-ghost.html#Synthetic-datasets)

Automates the selection of decision threshold for imbalanced classification task. The assumption for this method to work is the similar characteristics (like imbalance ratio) of training and test data. 

* [MOSES - Benchmarking platform for generative models (PyTorch Implementation)](https://arxiv.org/abs/1811.12823). [Github](https://github.com/molecularsets/moses)

Benchmarking platform to implement molecular generative models. It also provides a set of metrics to evaluate the quality and diversity of the generated molecules. A benchmark dataset (subset of ZINC) is provided for training the models. 

* [Reinvent 2.0 - an AI tool forr de novo drug design](https://chemrxiv.org/articles/preprint/REINVENT_2_0_an_AI_Tool_for_De_Novo_Drug_Design/12058026/1). [Github](https://github.com/MolecularAI/Reinvent)

Production-ready tool for de novo design from Astra Zeneca. It can be effectively applied on drug discovery projects that are striving to resolve either exploration or exploitation problems while navigating the chemical space. Language model with SMILE  output and trained by “randomizing” the SMILES representation of the input data. Implement reinforcement-leraning for directing the model towards relevant area of interest. 

* [Schnet by Jacobsen et. al. (Neural message passing)](https://arxiv.org/abs/1806.03146). [Github](https://github.com/atomistic-machine-learning/G-SchNet). [Tutorial](https://schnetpack.readthedocs.io/en/stable/tutorials/tutorial_03_force_models.html)

* [OpenChem](https://chemrxiv.org/articles/OpenChem_A_Deep_Learning_Toolkit_for_Computational_Chemistry_and_Drug_Design/12691943/1). [Github](https://github.com/Mariewelt/OpenChem)

* [DeepChem (Tensorflow)](https://github.com/deepchem/deepchem). [Website](https://deepchem.io) 

DeepChem aims to provide a high quality open-source toolchain that democratizes the use of deep-learning in drug discovery, materials science, quantum chemistry, and biology - from Github

* [ChemProp (Pytorch)](https://github.com/chemprop/chemprop)

Github repository for implmenting message passing neural networks for molecular property prediction as described in the paper [Analyzing Learned Molecular Representations for Property Prediction](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00237) by Yang et. al. 

* [Chainer-Chemistry](https://github.com/chainer/chainer-chemistry)

"Chainer Chemistry is a deep learning framework (based on Chainer) with applications in Biology and Chemistry. It supports various state-of-the-art models (especially GCNN - Graph Convolutional Neural Network) for chemical property prediction" - from their Github repo introduction

* [FastJTNN - python 3 version of the JT-NN](https://github.com/Bibyutatsu/FastJTNNpy3)

* [DimeNet++  - extension of Directional message pasing working (DimeNet)](https://arxiv.org/abs/2003.03123). [Github](https://github.com/klicperajo/dimenet)

* [BondNet - Graph neural network model for predicting bond dissociation energies, considers both homolytic and heterolytic bond breaking](https://github.com/mjwen/bondnet). [Github](https://github.com/mjwen/bondnet)

* [PhysNet](https://arxiv.org/pdf/1902.08408.pdf)

* [RNN based encoder software](https://github.com/ETHmodlab/BIMODAL)

* [AutodE](https://duartegroup.github.io/autodE/)

* [DScribe](https://singroup.github.io/dscribe/latest/)

* [RMG - Reaction Mechanism Generator](https://github.com/ReactionMechanismGenerator/RMG-Py)

Tool to generate chemical reaction networks. Includes Arkane, package for calculating thermodynamics from quantum mechanical calculations. 

* [PyePAL](https://pyepal.readthedocs.io/en/latest/?badge=latest)

Active learning approach to efficiently and confidently identify the Pareto front with any regression model that can output a mean and a standard deviation.

* [rxnfp](https://github.com/rxn4chemistry/rxnfp)

Github repository to generate chemical reaction fingerprints from reaction SMILES. 

* [mols2grid](https://github.com/cbouy/mols2grid)

Interactive chemical viewer for small molecules (RDKit wrapper)

* [molplotly](https://github.com/wjm41/molplotly)

Spotfire like capabilities to jupyter notebook. Medium article on explaining the MolPlotly. [Link](https://medium.com/@qcojuandavidmarin/molplotly-a-wonderful-tool-for-the-scientist-5ddb9a42c037?utm_source=pocket_saves)

* [ESPsim](https://github.com/hesther/espsim)

Calculate similarities of shapes and electrostatic potentials between molecules. Pen has a nice blogpost on using to estimate electronic similarities of common bioisosteres. [blog](https://iwatobipen.wordpress.com/2022/12/31/calculate-similarity-of-popular-bioisosters-rdkit-espsim-memo/)

## Datasets & Chemical libraries 


**Molecule datasets**

* PubChem: public sourced molecules 

* ChEMBL: bioactive molecules (most synthetic)

* SUREChEMBL: small molecules appearing in Patents 

* ZINC: collection of synthetic molecules (not all are bioactive) 

* QM 7/8/9: small molecules having not more than 7/8/9 heavy atoms 

* GDB-11

* [Papyrus](https://chemrxiv.org/engage/chemrxiv/article-details/617aa2467a002162403d71f0)

* [COCONUT](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00478-9): NP 400k there are some which are not NP 

* [Mcule](https://mcule.com/database/): Used in DEL enumerations 

* [DrugBank](https://go.drugbank.com/)

* [QMugs](https://www.nature.com/articles/s41597-022-01390-7)

QMugs (Quantum mechanical properties of drug-like molecules) collection comprises quantum mechanical properties of more than 665 k biologically and pharmacologically relevant molecules extracted from the ChEMBL database, totaling 2M conformers.

**Reaction Datasets**

* USPTO 
* Pistachio
* Reaxys
* Open Reaction Database 

**Commericial (building block) vendors**

* eMolecules building blocks 

* Enamine Fragments 

* WuXi GalaXi space 

* Otava's CHEMriya 

## Helpful utilities:

* [RD-Kit](https://github.com/rdkit/rdkit)
    * [Get Atom Indices in the SMILE:](https://colab.research.google.com/drive/16T6ko0YE5WqIRzL4pwW_nufTDn7F3adw)
    * [Datamol for manipulating RDKit molecules](https://github.com/datamol-org/datamol)
    
* [Papers with code benchmark for QM9 energy predictions](https://paperswithcode.com/sota/formation-energy-on-qm9)

* [MOSES: Molecular generation models benchmark](https://github.com/molecularsets/moses)

* [Therapeutics Data Commons](https://tdcommons.ai)
"Therapeutics Data Commons is an open-science platform with AI/ML-ready datasets and learning tasks for therapeutics, spanning the discovery and development of safe and effective medicines. TDC also provides an ecosystem of tools, libraries, leaderboards, and community resources, including data functions, strategies for systematic model evaluation, meaning"