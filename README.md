# Stereotypes Report
Comparing stack overflow survey results vs national salary levels to assess some contentious stereotypes

The results are published on [Medium](https://medium.com/@wgilpin/stereotypes-meet-data-933ff18ed30).

### Motivation

There were two motivations for the project. Firstly I am personally interested in the intersection between society and technology, and feel that too much of public debate is ill-informed. We are all guilty of lazy thinking - we see a conclusion we like, then we forever after quote it as gospel, rarely digging into the underlying assumptions or data, and just as rarely do we reassess the validity of our "knowledge" in the light of later evidence. This piece of works will, of course, make minimal impact on the wider problem, but we do what we can.

Secondly, I am undertaking Udacity's Data Science Nanodegree, and this piece of work fit in nicely with a required small project there :)

### Installation

The notebook was executed under Anaconda base installation on Windows. You'll require at least the following otherwise:

- python 3.x
- pandas
- numpy

### Data

The data files can be found as follows:

- [CIA World Factbook 2016]( https://www.cia.gov/library/publications/the-world-factbook/)

- [Stack Overflow Survey Results 2018](https://insights.stackoverflow.com/survey)

The CSV files will need to be in the same location as the Jupyter notebook

### Results

TL;DR the stereotypes I investigated were not supported by the data available, at least in relation to Stack Overflow users.

There were however a few interesting patterns worth pointing out, all of which are, however, weak effects:

- Average salary vs education spends shows a lot of variability in poorer countries, but the richer countries seem to show a correlation — higher salaries increases with higher spending on education. My blog posts suggests some possible interpretations.
- Older populations earn more. Or is it that richer countries have more of the older engineers?
- Richer nations to skip fewer meals for work. I know I rarely do! 

Discussion of all these is to be found in the [blog post](https://medium.com/@wgilpin/stereotypes-meet-data-933ff18ed30)

### Acknowledgements

No other students or their projects were consulted in the creation of this work, however Stack Overflow itself was consulted regularly to solve specific small tasks with pandas, primarily. For example [filtering outliers][https://stackoverflow.com/questions/23199796/detect-and-exclude-outliers-in-pandas-dataframe] and the [conversion of CIA Factbook data into CSV format](https://github.com/thewiremonkey/factbook.csv)
