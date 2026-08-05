# College Major Recommendation System (Science & Tech)

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://majorrec-nicho365.streamlit.app/)

A data-driven web application designed to help prospective university students objectively identify the most relevant majors and universities. Powered by the **K-Nearest Neighbors (KNN)** algorithm, the system compares a candidate's 8 subtest scores against **86,000+ historical UTBK 2019 data points** to find similarity patterns (similar to alumni profiles) and generate realistic recommendation lists.

## Background

Choosing a college major is often a confusing and critical phase for high school graduates. Decision-making is frequently driven by assumptions, social pressure, or unverified information.

This project delivers an objective, data-driven alternative. By mapping an individual's 8 subtest scores against tens of thousands of historical acceptance records, the system identifies admission tendencies and provides tailored recommendations for both majors and universities.

## Key Features

* **Comprehensive Subtest Input:** Evaluates scores across all 8 UTBK Saintek subtests.
* **KNN-Based Pattern Matching:** Matches applicant profiles against 86,000+ historical records to identify nearest neighbors (alumni profile trends).
* **Realistic Recommendations:** Outputs a prioritized list of relevant majors and institutions based on score suitability.
* **Interactive UI:** Built and deployed using Streamlit for an accessible and responsive user experience.


## 🛠️ Data & Machine Learning

* **Dataset:** 86,000+ historical records from UTBK 2019 (Saintek stream).
* **Algorithm:** K-Nearest Neighbors (KNN).
* **Evaluated Features (8 Subtests):**
  * General Reasoning (Penalaran Umum)
  * Reading & Writing Comprehension (Pemahaman Bacaan & Membaca)
  * General Knowledge & Understanding (Pengetahuan & Pemahaman Umum)
  * Quantitative Ability (Kuantitatif)
  * Saintek Mathematics (Matematika Saintek)
  * Physics (Fisika)
  * Chemistry (Kimia)
  * Biology (Biologi)

## Tech Stack

* **Language:** Python
* **Machine Learning & Data Processing:** Scikit-Learn, Pandas, NumPy
* **Web Framework:** Streamlit

