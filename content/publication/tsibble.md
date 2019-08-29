+++
abstract = """
Mining temporal data for information is often inhibited by a multitude of formats: irregular or multiple time intervals, point events that need aggregating, multiple observational units or repeated measurements on multiple individuals, and heterogeneous data types. On the other hand, the software supporting time series modeling and forecasting, makes strict assumptions on the data to be provided, typically requiring a matrix of numeric data with implicit time indexes. Going from raw data to model-ready data is painful. This work presents a cohesive and conceptual framework for organizing and manipulating temporal data, which in turn flows into visualization, modeling and forecasting routines. Tidy data principles are extended to temporal data by: (1) mapping the semantics of a dataset into its physical layout; (2) including an explicitly declared index variable representing time; (3) incorporating a "key" comprising single or multiple variables to uniquely identify units over time. This tidy data representation most naturally supports thinking of operations on the data as building blocks, forming part of a "data pipeline" in time-based contexts. A sound data pipeline facilitates a fluent workflow for analyzing temporal data. The infrastructure of tidy temporal data has been implemented in the R package **tsibble**.
"""
abstract_short = ""
authors = ["Earo Wang", "Dianne Cook", "Rob J Hyndman"]
date = "2019-01-30"
image_preview = ""
math = true
publication_types = ["3"]
publication = ""
publication_short = ""
selected = true
title = "A new tidy data structure to support exploration and modeling of temporal data"
url_code = "https://github.com/earowang/paper-tsibble"
url_arxiv = ""
url_doi = ""
url_pdf = "http://pdf.earo.me/tsibble.pdf"

+++

```{txt}
@misc{,
  Author = {Earo Wang and Dianne Cook and Rob J Hyndman},
  Title = {A new tidy data structure to support exploration and modeling of temporal data},
  Year = {2019},
  Eprint = {arXiv:1901.10257},
}
```

The accompanying R package **tsibble** has won the John Chambers Statistical Software Award in 2019. 