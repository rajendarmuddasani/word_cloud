# Word Cloud Visualization for Course Titles

This notebook generates a **Word Cloud** from online course titles to visualize the most frequent keywords in the course catalog.  
It uses real course metadata from an open dataset and Python visualization libraries.

---

## Features

- Loads course metadata from a public CSV file.
- Cleans and combines all course titles into a single text.
- Removes common and custom stopwords for clarity.
- Generates and displays a word cloud image using `wordcloud` and `matplotlib`.

---

## How to Run

1. **Clone or download this repository.**

2. **Install required packages:**
    ```bash
    pip install pandas matplotlib seaborn wordcloud
    ```

3. **Open `word_cloud.ipynb` in Jupyter Notebook or VS Code.**

4. **Run all cells.**
    - The notebook will download the dataset, process the titles, and display the word cloud.

---

## Example Output

The word cloud will highlight popular keywords such as:
- python
- data
- machine learning
- cloud
- ai
- tensorflow

---

## Dataset Sources

- [Course Metadata CSV](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-ML321EN-SkillsNetwork/labs/datasets/course_genre.csv)

---

## License

This notebook is for educational and demonstration purposes only.  
Dataset © IBM Corporation.

---
