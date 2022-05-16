<h2 align="center">MEDLINE</h2>

## Task Description

The task is to web scrape the [MEDLINE](https://www.nlm.nih.gov/medline/) biomedical literature database and extract
the following information: Keywords (Covid-19, Booster, mRNA, Vaccine, Obesity, Cancer), Abstract and Title. Analyze
and visualize the data using statistical tests and uni-variate analysis.

Some techniques used are:

- Web Scraping with BeautifulSoup and Selenium
- Statistical tests (t-test, Mann-Whitney U, Kruskal-Wallis H etc.)
- Uni variate analysis (Boxplot, Histogram, QQ-plot, Scatter-plot, Correlation Matrix etc.)
- Effect size measures (Cohen's d)

## About the dataset

MEDLINE is a bibliographic database of life sciences and biomedical information. The United States National Library of
Medicine (NLM) at the National Institutes of Health maintains the database as part of the Entrez information retrieval
system. MEDLINE is the primary database for biomedical and life sciences journal articles. It contains over 27 million
citations from more than 5,600 scientific journals.

## Dependencies

List of all the libraries you need to run the code.

  ```sh
pandas
pymed
numpy 
re
matplotlib
seaborn
  ```

## Usage

  ```sh
  $ conda create -n "env-name" python=3.x, anaconda, pymed
 
  $ conda activate "env-name"
  
  $ cd Mining-MEDLINE
  
  $ jupyter notebook
  ```

## View code

[NBviewer](https://nbviewer.org/github/vineetver/Mining-MEDLINE/blob/main/medline.ipynb)

## License

Distributed under the MIT License. See `LICENSE.md` for more information.

## Contact

Vineet Verma - vineetver@hotmail.com - [Goodbyeweekend.io](https://www.goodbyeweekend.io/)
