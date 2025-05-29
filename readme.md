
# Resume Screening using NLP

An intelligent, automated resume screening system powered by Natural Language Processing (NLP). This tool enables recruiters and HR professionals to identify the most relevant resumes for a given job role efficiently.

![logo](https://github.com/user-attachments/assets/c0a31d1d-e753-4573-bbfe-61984fcc0851)

---

## Features

- **Resume-Job Matching**: Automatically compares resumes with job descriptions using semantic similarity.
- **Preprocessing Pipeline**: Cleans and prepares textual data for meaningful analysis.
- **TF-IDF & Embedding Models**: Implements vectorization techniques to extract insights.
- **Streamlit Dashboard**: Easy-to-use interactive dashboard for viewing results.
- **Batch Processing**: Supports bulk analysis of multiple resumes and job roles.

---

## Getting Started

### Setup

Clone the repository and install the required Python dependencies:

```bash
cd /path/to/your/folder
pip install -r requirements.txt
```

### Run the Application

Navigate to the main app directory and start the Streamlit server:

```bash
cd main_web_app
streamlit run app.py
```

The app should automatically open in your browser at `http://localhost:8501/`.


---

## Core Modules

> These are compiled `.pyc` files used by the app:

* `Cleaner.cpython-310.pyc`: Text preprocessing and normalization
* `Distill.cpython-310.pyc`: Keyphrase extraction from job descriptions
* `Similar.cpython-310.pyc`: Resume-job similarity calculations
* `tf_idf.cpython-310.pyc`: TF-IDF based keyword importance scorer

Ensure these are in the environment or recompile if you update logic.

---


## Acknowledgements

Thanks to the open-source community and the developers of:

* **SpaCy**
* **NLTK**
* **Scikit-learn**
* **Streamlit**



<sub> CREATED BY: RESHMA MERIN THOMAS </sub>
