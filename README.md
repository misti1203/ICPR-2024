# Uncertainty-RIFA-Net: Uncertainty Aware Robust Information Fusion Attention Network for Brain Tumors Classification in MRI Images

## Abstract
Malignant brain tumors pose a significant global threat, emphasizing the critical need for efficient diagnostic methods utilizing MRI. Manual analysis of MRI images is labor-intensive and subjective, highlighting the necessity for faster and automated effective methods.  

In this paper, we propose an **uncertainty-aware robust information fusion attention network** model for precisely classifying brain tumors in MRI images. Our approach introduces a novel **robust information fusion attention layer** that learns enhanced representations by integrating global context with local information. We estimate the uncertainty in our model's predictions using the **ensemble Monte Carlo dropout strategy**.  

Our findings demonstrate outstanding performance, achieving accuracies of:
- **98.37%** on the *Cheng* dataset  
- **98.48%** on the *Nickparvar* dataset  

These results highlight the efficacy of our approach in brain tumor MRI image classification tasks while minimizing computational costs in terms of resource usage and inference time.

---

## Key Highlights
- **Novel Attention Mechanism**: Introduced a robust information fusion attention layer to enhance representation learning.
- **Uncertainty Estimation**: Leveraged the ensemble Monte Carlo dropout strategy for reliable predictions.
- **High Accuracy**: Achieved state-of-the-art accuracy on benchmark datasets for brain tumor classification.

Proposed Uncertainty-RIFA-Net:
![Proposed Method](Figure1.pdf "Uncertainty-RIFA-Net")


## Datasets
- **Cheng Dataset**  
- **Nickparvar Dataset**

## Performance Metrics
| Dataset       | Accuracy (%) |
|---------------|--------------|
| Cheng         | 98.37        |
| Nickparvar    | 98.48        |


![Figure 2: Results](fig_explainable.pdf "Score-CAM")
---

## Citation
If you use this work, please cite:  
>Dhar, J., Rana, K., Goyal, P. (2025). *Uncertainty-RIFA-Net: Uncertainty Aware Robust Information Fusion Attention Network for Brain Tumors Classification in MRI Images*. In: Antonacopoulos, A., Chaudhuri, S., Chellappa, R., Liu, CL., Bhattacharya, S., Pal, U. (eds) **Pattern Recognition. ICPR 2024**. Lecture Notes in Computer Science, vol 15327. Springer, Cham. [https://doi.org/10.1007/978-3-031-78398-2_21](https://doi.org/10.1007/978-3-031-78398-2_21)

---

Feel free to open issues or contribute to this project!  
