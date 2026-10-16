# 🧪 Joule's Law & Specific Heat Capacity Virtual Lab
**----------------------------------------------------------------------**
Provided website: https://montreeph-kosen-kmitl.github.io/joule-lab/
**----------------------------------------------------------------------**
Welcome to the **Joule's Law & Specific Heat Capacity Virtual Laboratory**—an interactive simulation web application designed for learning and teaching physics concepts related to **Joule's Law** and **Specific Heat Capacity**.

---

## 🎯 Learning Objectives

1. **Understand Joule's Law ($P = IV = I^2R$):** Investigate the relationship between voltage ($V$) and current ($I$) to determine the resistance ($R$) of the heating element.
2. **Explore Thermal Energy Transfer:** Observe the conversion of electrical energy into thermal energy inside a calorimeter ($\Delta Q = m c \Delta T$).
3. **Determine Specific Heat Capacity ($c$):** Calculate and compare the specific heat capacity of water ($c_{\text{water}}$) and ethanol ($c_{\text{ethanol}}$).
4. **Analyze Thermodynamic System Models:**
   * **Isolated System:** Ideal scenario assuming zero thermal loss to the environment.
   * **Closed System:** Realistic model incorporating heat loss based on Newton's Law of Cooling.
5. **Develop Data Analysis Skills:** Export experimental data to `.csv` format, plot graphs, and perform linear regression (slope calculation) using spreadsheet tools like Microsoft Excel or Google Sheets.

---

## 📑 Laboratory Structure

The virtual experiment is organized into **4 main tabs**:

* **Tab 0: Guidance & Report**
  * Embedded PDF view of the lab guide (`guidance.pdf`).
  * Direct download link for the student lab report template (`report.pdf`).
  * Instructions for submission via Google Classroom.

* **Tab 1: Part 1 - Resistance ($R$)**
  * Adjust applied voltage ($V$) to measure circuit current ($I$).
  * Record data points to build a $V$ vs. $I$ graph and derive heater resistance ($R$).

* **Tab 2: Part 2 - Heating Water**
  * Select the thermodynamic model (**Isolated** vs. **Closed System**).
  * Configure volume ($V_{\text{vol}}$), initial temperature ($T_i$), target temperature ($T_f$), and voltage ($V$).
  * Real-time graphical visualization of temperature over time ($T$ vs. $t$).

* **Tab 3: Part 3 - Heating Ethanol**
  * Conduct ethanol heating simulations under a **Closed System**.
  * Compare the heating rate of ethanol against water under identical electrical power input.

---

## 🚀 Quick Start & User Guide

### For Students

1. **Access the Lab:** Open the provided website link in your web browser.
3. **Review Instructions:** Navigate to **Tab 0: Guidance & Report** to read the instructions and download `report.pdf`.
4. **Perform Experiments:**
   * **Part 1:** Adjust the voltage slider and click **"Record Current (I)"** to populate the data table.
   * **Part 2 & 3:** Set your desired liquid parameters and click **"Start Heating"** to run the simulation.
5. **Export Data:** Click **"Download CSV"** in any section or use the **"📦 Download All Parts (Combined CSV)"** button in the top navigation bar.
6. **Data Analysis:** Open the exported `.csv` file in Excel or Google Sheets to generate graphs, calculate slope values, and determine $R$ and $c$.
7. **Submit:** Fill in your findings in the report sheet and turn it in via **Google Classroom**.

---

## 📂 Repository Structure

```
├── index.html        # Main Virtual Lab application (HTML + Tailwind CSS + JS)
├── guidance.pdf      # Lab guidelines and theoretical documentation
├── report.pdf        # Student lab report template
└── README.md         # Project documentation (this file)
```

---

## 🛠️ Tech Stack

* **HTML5 & Vanilla JavaScript (ES6+):** Pure client-side physics simulation engine for fast, responsive, and serverless execution.
* **Tailwind CSS:** Modern, responsive UI design framework.
* **Chart.js:** Interactive real-time plotting for temperature trends.
* **HTML5 Canvas API:** Custom visual graphics for calorimeter heating and bubble animations.
