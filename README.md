# Political-analysis
We present a large-scale topic modeling study of Tamil political discourse on YouTube collected between January
2025 and September 2025. Using 100,000 user comments scraped via BeautifulSoup, we apply a transformer-based
BERTopic pipeline with dynamic topic reduction (automatic nr_topics) and multilingual BERT embeddings to detect
salient political themes. We compare BERTopic’s outputs with classical baselines (LDA and NMF) on standard
coherence metrics (Cv and NPMI) and through human interpretability assessments. Our results show that dynamic
BERTopic yields more coherent, interpretable, and fine-grained political topics in Tamil than classical approaches,
uncovering themes such as leadership evaluation, regional policy grievances, election mobilization, caste- and identity-
based conversations, and media critique. We discuss methodological adaptations required for Tamil social text (script
variations, transliteration), ethical considerations in political text mining, and implications for computational social
science. Code, aggregated topic tables, and (anonymized) dataset statistics are provided to enable reproducibility.
