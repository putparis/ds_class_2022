- [2602454: Business Intelligence System](#2602454-business-intelligence-system)
  - [week 1: 12-Jan-2022](#week-1-12-jan-2022)
    - [Intro to data science](#intro-to-data-science)
    - [Basic Command line](#basic-command-line)
      - [Windows command line](#windows-command-line)
      - [macOS Terminal command line](#macos-terminal-command-line)
    - [Video tutorials](#video-tutorials)
    - [Recommended resources](#recommended-resources)
---
# 2602454: Business Intelligence System
* github: https://github.com/prasertcbs/ds_class_2021
* [cheat sheet](https://github.com/prasertcbs/cheatsheet) 

## week 1: 12-Jan-2022
### Intro to data science
* [ ] [Data Science in Busines](./cheatsheet/ds%20for%20business.pdf)
* [ ] [CRISP model: CRoss-Industry Standard Process for data mining](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining#/media/File:CRISP-DM_Process_Diagram.png)
* [ ] [machine learning](https://jakevdp.github.io/PythonDataScienceHandbook/05.01-what-is-machine-learning.html)
* [ ] TARGET teenage pregnancy case 2012
  * [ ] [New York Times](https://www.nytimes.com/2012/02/19/magazine/shopping-habits.html)
  * [ ] [Forbes](https://www.forbes.com/sites/kashmirhill/2012/02/16/how-target-figured-out-a-teen-girl-was-pregnant-before-her-father-did/?sh=5199355b6668)
  * [ ] [video clip](https://nyti.ms/2kH3YzT)
* [ ] [Netflix: the social dilemma](https://www.netflix.com/th-en/title/81254224)
* [ ] [Netflix: the great hack](https://www.netflix.com/th-en/title/80117542)
    * [ ] [wiki](https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal)
* [ ] explore data
  * [ ] sample data:
    * [ ] [bigmac index](example/bigmac_index.csv)
    * [ ] [telecom customer churn](ml/telecom-churn-prediction.ipynb)
    * [ ] [food nutrition](example/nutrients.csv)
    * [ ] [interactive notebook](example/interactive_dataframe_mcdonald.ipynb)
* [ ] pandas vs sql
    * [ ] [pandas](https://www.youtube.com/watch?v=f3CLdRl-zyQ&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz)
    * [ ] [from SQL to pandas](example/postgres_sql_vs_pandas.ipynb)
    * [ ] 
* [ ] Install Python and packages
  * [ ] installation:
    * [ ] [Install Python using miniconda](https://www.youtube.com/watch?v=NxIwWGKuSco&list=PLoTScYm9O0GH4YQs9t4tf2RIYolHt_YwW&index=4)
```sh
pip install -U nodejs
pip install -U jupyterlab ipywidgets
pip install -U pandas matplotlib seaborn scipy scikit-learn joblib lxml beautifulsoup4 pillow sqlalchemy openpyxl xlrd statsmodels tabulate pandas-datareader
pip install -U plotly cufflinks chart_studio kaleido orjson
pip install -U psycopg2-binary
pip install -U ipython-sql pgspecial
pip install -U graphviz
pip install -U xgboost catboost lightgbm shap
pip cache purge
```
### Basic Command line
#### [Windows command line](https://www.youtube.com/watch?v=C5fCLAA7Mmc&list=PLoTScYm9O0GGpQRdTu3Y8sGA8MsBuojhV)
* [ ] `dir`: list files
* [ ] `md`: make directory
* [ ] `cd`: change directory
* [ ] `copy`: copy file
* [ ] `move`: move file
* [ ] `del`: delete file
#### [macOS Terminal command line](https://www.youtube.com/watch?v=-5SI3xFM_3E&list=PLoTScYm9O0GGWXd_4sYsADmM4og6vU1Zh)
* [ ] `ls`: list files
* [ ] `mkdir`: make directory
* [ ] `cd`: change directory
* [ ] `cp`: copy file
* [ ] `mv`: move file
* [ ] `rm`: delete file
* [ ] `man`: command manual
### Video tutorials
* [ ] [Python programming](https://www.youtube.com/watch?v=bu6kwrpOqFM&list=PLoTScYm9O0GH4YQs9t4tf2RIYolHt_YwW)
* [ ] [JupyterLab](https://www.youtube.com/watch?v=3PkMNsUCAM0&list=PLoTScYm9O0GEour5CiwfSnoutg3RyA76O)
* [ ] [learn pandas](https://www.youtube.com/watch?v=f3CLdRl-zyQ&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz)
* [ ] [learn numpy](https://www.youtube.com/watch?v=ts2L5mtMMi8&list=PLoTScYm9O0GFNEpzsCBEnkUwgAwOu_PWw)
* [ ] [learn matplotlib](https://www.youtube.com/watch?v=WOEOH8OV99k&list=PLoTScYm9O0GGRvUsTmO8MQUkIuM1thTCf)
* [ ] [learn seaborn](https://www.youtube.com/watch?v=TJ2xK3AV5RQ&list=PLoTScYm9O0GGC9QvLlrQGvMYatTjnOUwR)
* [ ] [learn scikit-learn](https://www.youtube.com/watch?v=AdDvPCarDyI&list=PLoTScYm9O0GH_3VrwwnQafwWQ6ibKnEtU)
* [ ] [basic command line](https://www.youtube.com/playlist?list=PLoTScYm9O0GFpyK3BixJNjkPBUhJuPCl-)
* [ ] [basic github](https://www.youtube.com/watch?v=hSQgAA8bj6I&list=PLoTScYm9O0GGsV1ZAyP4m_iyAbflQrKrX)
### Recommended resources
* [ ] [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)
  * [ ] [Jupyter Notebook on github](https://github.com/jakevdp/PythonDataScienceHandbook)
* [ ] [cheat sheet](https://github.com/prasertcbs/cheatsheet)
* [ ] [pandas documentation](https://pandas.pydata.org/docs/)
* [ ] [Kaggle](https://www.kaggle.com/)
* [ ] [Stack Overflow](https://stackoverflow.com/)
* [ ] Stack Overflow survey
  * [ ] [2018](https://insights.stackoverflow.com/survey/2018#technology)
    * [ ] [popular](https://insights.stackoverflow.com/survey/2018#technology-_-databases)
    * [ ] [most loved](https://insights.stackoverflow.com/survey/2018#technology-_-most-loved-dreaded-and-wanted-databases)
  * [ ] [2020](https://insights.stackoverflow.com/survey/2020#most-popular-technologies)
    * [ ] [popular](https://insights.stackoverflow.com/survey/2020#technology-databases)
    * [ ] [most loved](https://insights.stackoverflow.com/survey/2020#technology-most-loved-dreaded-and-wanted-databases)
  * [ ] [2021](https://insights.stackoverflow.com/survey/2021#technology-most-popular-technologies)
    * [ ] [popular](https://insights.stackoverflow.com/survey/2021#section-most-popular-technologies-databases)
    * [ ] [most loved](https://insights.stackoverflow.com/survey/2021#section-most-popular-technologies-databases)
