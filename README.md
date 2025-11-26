# Discovery of Novel Psychedelic-Like 5-HT2A Ligands for Behavioral Addiction Treatment

**Portfolio project – Computational Drug Discovery (2025)**

## Scientific Question
Can we use public data to find new drug candidates that mimic the therapeutic effects of psilocybin and LSD on behavioral addictions (gambling disorder, gaming addiction, compulsive buying) via 5-HT2A receptor activation?

## Key Results
- Classic psychedelics (LSD, psilocin, DMT, etc.) form a **distinct, isolated structural island** in chemical space — completely separate from classical antipsychotics
- This "psychedelic island" is highly enriched in potent 5-HT2A ligands
- Identified **15 previously unexplored molecules** with nanomolar affinity structurally belonging to the psychedelic chemotype
- **Top hit: CHEMBL65547** — pChEMBL = 8.08 (IC₅₀ ≈ 8 nM) — one of the most potent 5-HT2A ligands in ChEMBL

## Methods
- ChEMBL human 5-HT2A dataset (~6,500 unique compounds)
- Morgan fingerprints + UMAP + HDBSCAN
- Virtual screening combining structural similarity and binding potency

## Figures
**Figure 1** – Clean chemical space with reference compounds  
**Figure 2** – Annotated view showing psychedelic vs antagonist-rich clusters

These molecules represent high-priority candidates for next-generation therapeutics targeting psychological rigidity in behavioral addictions.

**Tools**: Python • RDKit • UMAP • HDBSCAN • Matplotlib
