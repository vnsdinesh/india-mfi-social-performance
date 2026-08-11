# India MFI Social Performance: Data and Analysis

This repository contains the data processing and analysis materials for the working paper:

> Pandey, D. K. (2026). Does financial inclusion create social value? State-level evidence from India (Working Paper 1).

The paper examines whether financial inclusion and social value move together across Indian states using composite indices for financial inclusion (FIIndex) and an SROI-inspired social-value measure (SROIMetrics), based on official state-level data.

## Repository contents

- `Pandey_D_K_2026_MFI_SROI_Social_Value_Paper1.pdf`  
  PDF of the SSRN working paper.

- `MFI_SROI_Social_Value_Data_Analysis.ipynb`  
  Jupyter notebook showing the main data cleaning, index construction (FIIndex, SROIMetrics, SROIMetrics_nonoverlap) and regression analysis.

- `Fig1_Conceptual_Framework.png`  
  Conceptual framework linking financial inclusion, stakeholder outcomes and social value.

- `Fig2_FIIndex_SROIMetrics_nonoverlap.png`  
  Scatterplot of FIIndex and the non-overlapping social-value measure.

- `Fig3_Correlation_Heatmap.png`  
  Correlation heatmap for FIIndex, SROIMetrics, SROIMetrics_nonoverlap and key state-level indicators.

- `Fig4_State_level_Dist.png`  
  State-level distribution of FIIndex.

- `Fig5_SHG_Microfinance.png`  
  Comparison of SHG microfinance engagement and formal financial depth for selected states.

- `Fig6_Log_Deposits.png`  
  Relationship between log deposits and average hospital expenditure (exploratory health-outcome regression).

- `.gitignore`  
  Ensures that raw data folders (e.g. `Data_downloaded/`) and system files (`.DS_Store`, `.ipynb_checkpoints/`) are not tracked in the public repo.

## Data sources

The analysis uses publicly available, aggregate state-level data from:

- Reserve Bank of India (RBI) – state-wise deposits and banking indicators.  
- NABARD – *Status of Microfinance in India 2017–18* and related SHG reports.  
- Census of India 2011 – rural households and population.  
- MOSPI / HCES – rural and urban MPCE and health-related indicators.  
- PLFS – state-level literacy rates.  
- NPCI – UPI product statistics and other digital-payment indicators.

Raw source files are **not** redistributed in this repository. They should be obtained directly from the original providers using the references and links provided in the working paper.

## Reproducibility

To reproduce parts of the analysis:

1. Clone this repository:
   ```bash
   git clone https://github.com/vnsdinesh/india-mfi-social-performance.git
   ```
2. Obtain the required raw state-level data from RBI, NABARD, Census of India, MOSPI/HCES, PLFS and NPCI as cited in the paper.
3. Place the raw data in your own local directory (e.g. `Data_downloaded/`), and adjust file paths in the notebook if necessary.
4. Open `MFI_SROI_Social_Value_Data_Analysis.ipynb` in Jupyter and execute the cells in order.

## Citation

If you use this repository or the working paper, please cite:

> Pandey, D. K. (2026). Does financial inclusion create social value? State-level evidence from India (Working Paper v1.0). Available at SSRN and GitHub: https://github.com/vnsdinesh/india-mfi-social-performance.

## Contact

Questions and feedback are welcome. Please contact:

- Dinesh Kumar Pandey  
- vnsdinesh@gmail.com; Pandey-D@ulster.ac.uk