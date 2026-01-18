# Dual-Stream-ECG-Fusion
# A Dual-Stream Signal Fusion Framework for Interpretable ECG Diagnosis

This repository contains the supplementary data, metadata, and reproducibility resources for the paper: **"A Dual-Stream Signal Fusion Framework for Interpretable ECG Diagnosis: Surpassing Commercial Diagnostic Standards"** (Submitted to IEEE Journal of Biomedical and Health Informatics).

## 📂 Repository Contents

This dataset provides the specific metadata, label mappings, and data splits used to train and validate the Dual-Stream Hybrid Model.

* **`metadata/`**: Contains the processed label files.
    * `ptbxl_statements.csv`: Diagnostic statements derived from the PTB-XL dataset (Human annotations).
    * `12sl_statements.csv`: Diagnostic statements extracted from the Marquette 12SL™ algorithm.
    * `snomed_description.csv`: Mapping of diagnostic codes to SNOMED CT terms.
* **`RECORDS`**: The complete list of ECG records used in this study.
* **`integrity/SHA256SUMS.txt`**: Checksums to verify file integrity.
* **`LICENSE.txt`**: Licensing information for this dataset.

## 🚀 Usage & Reproducibility

These files are designed to be used in conjunction with the original **PTB-XL** and **PTB-XL+** datasets available on PhysioNet.

1.  **Data Source:** Download the raw waveform data from [PhysioNet PTB-XL](https://physionet.org/content/ptb-xl/).
2.  **Mapping:** Use `ptbxl_statements.csv` and `12sl_statements.csv` provided here to reproduce the exact training/test splits (Fold 1-10) described in the manuscript.

## 📝 Citation

If you use this metadata in your research, please cite our paper:

> Chuelwon Lee, "A Dual-Stream Signal Fusion Framework for Interpretable ECG Diagnosis: Surpassing Commercial Diagnostic Standards," IEEE Journal of Biomedical and Health Informatics (Under Review), 2026.

## 👤 Author

**Chuelwon Lee**
* RAQA Team, HUINNO Co., Ltd.
* Contact: this14@naver.com
