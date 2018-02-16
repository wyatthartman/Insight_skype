## Microbes and C cycling: short code demo in R.

This repo contains R code demonstrating a rather simple analysis of microbial genes related to soil carbon turnover.  

This analysis was used in producing the journal article "A genomic perspective on stoichiometric regulation of soil carbon cycling", published in the ISME Journal in 2017.
The included article is open access, and on the web at https://www.nature.com/articles/ismej2017115.  A simplified explanation of the research for the general public can be found here: https://jgi.doe.gov/scaling-microbial-genomics-discoveries-ecosystem-modeling/

The notebook here shows calculation and plotting of genes correlated with soil carbon turnover (C turnover), and relationships between C turnover and categories of these genes aggregated by their role in soil carbon (C), nitrogen (N) and phosphorus (P) cycling.
The notebook takes as input 1) soil chemistry observations, with carbon cycling; 2) soil microbial genes per sample; and 3) a list of genes involved in cycling of soil C, N, and P.
The script obtains abundance data for the subset of C, N, and P genes, and displays their filtered correlations with C turnover on a heatmap of scaled abundances per sample.  Relationships between gene abundances and soil C turnover appeared clustered by category of C, N, and P cycling.  The code compiles aggregated gene abudances by six categories of C, N, and P cycling, and shows these aggregate categories are highly correlated with the relative availability of nitrogen and phosphorus in soil (soil N:P).

Interpretation of these patterns is given in the notebook and in detail in the publication, which explores in depth how underlying genomes are selected by environmental factors, producing the aggregate patterns shown in the notebook.