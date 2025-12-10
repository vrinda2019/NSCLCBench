# NSCLCBench

NSCLCBench: Benchmarking Clinical Trial Q&A with LLMs and RAG

NSCLCBench is a lightweight benchmark designed to evaluate how well Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) systems answer core evidence-based questions about Phase 3 non-small cell lung cancer (NSCLC) clinical trials. It provides a structured evaluation pipeline to test extraction accuracy, endpoint reasoning, and hallucination control.

What This Benchmark Evaluates

NSCLCBench contains four key question types commonly used in clinical trial analysis:
1. Trial Counting:
How many Phase 3 NSCLC trials were conducted in the last 10 years?
2. Primary Endpoint Identification:
What is the most common primary outcome measure?
3. PRO/COA Inclusion Detection:
Of those trials, how many included patient-reported outcomes(PROs) (or clinical outcome assessments [COAs]) as a secondary objective?
4. PRO/COA Instrument Extraction:
Which PROs/COAs were included as secondary endpoints?

These tasks measure numeric reasoning, evidence retrieval, classification, and extraction quality.
