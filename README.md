# 🫀 PULSE–HF: Predicting Worsening Left Ventricular Function in Heart Failure Patients from ECGs

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Paper](https://img.shields.io/badge/paper-eClinicalMedicine-blue)](https://www.thelancet.com/journals/eclinm/article/PIIS2589-5370(26)00030-1/fulltext)

**PULSE–HF** is a deep learning framework that forecasts whether a patient’s **left ventricular ejection fraction (LVEF)** will decline below **40% within one year** based on a **standard 12-lead ECG** and **prior LVEF measurements**. It is designed specifically for patients with a history of heart failure.

![Figure](pulsehf.png)
---

## 📄 Read the Paper

> 📘 **Published in eClinicalMedicine**:  
> **"Forecasting left ventricular systolic dysfunction in heart failure with artificial intelligence"**  
> by Teya Bergamaschi*, Tiffany Yau*, Payal Chandak*, Abena Kyereme-Tuaha, Judy Hung, Hanna Gaggin, Isaac S. Kohane, and Collin M. Stultz  
> (* equal contribution)  
> 🧾 [Access the paper here](https://www.thelancet.com/journals/eclinm/article/PIIS2589-5370(26)00030-1/fulltext)

---

## 🧠 Why PULSE-HF?

Heart failure is a major public health burden, with five-year mortality rates exceeding 50%. In heart failure patients with preserved ejection fraction, the ability to anticipate worsening systolic function—before symptoms emerge—opens new doors for:

- 🕒 **Early intervention**
- 📉 **Improved prognostication**
- 💊 **Timely therapy initiation**
- 🏥 **Optimized echocardiogram scheduling**

> ⚠️ Existing EHR-based models achieve only 54–68% AUROC for this task. PULSE-HF hits **~92% AUROC** across multiple institutions.

---

## 🔍 What Does PULSE-HF Do?

PULSE–HF forecasts whether a patient's **LVEF will fall below 40%** within **1 year** after an ECG is taken. It does this by combining:

- 🖥️ **Raw 12-lead ECG waveform data**
- 📊 **History of past LVEF values**

It also includes a **Lead I version** that performs comparably—ideal for **wearables** or **home-based monitoring**.  
Model weights can be downloaded from [this link](https://huggingface.co/teyaberg/PULSE-HF).

---

## 📜 Cite us

If you find this work helpful, please reference:
```
@article{bergamaschi2026pulsehf,
  title={Forecasting left ventricular systolic dysfunction in heart failure with artificial intelligence},
  author={Bergamaschi, Teya and Yau, Tiffany and Chandak, Payal and Kyereme-Tuah, Abena and Hung, Judy and Gaggin, Hanna and Kohane, Isaac S. and Stultz, Collin M.},
  journal={eClinicalMedicine},
  year={2026},
  volume={92},
  doi={10.1016/j.eclinm.2026.103783},
}
```
