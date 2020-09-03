# Wrangle-and-Analyze-Data


## Project Details

Your tasks in this project are as follows:

-   Data wrangling, which consists of:
    -   Gathering data (downloadable file in the Resources tab in the left most panel of your classroom and linked in step 1 below).
    -   Assessing data
    -   Cleaning data
-   Storing, analyzing, and visualizing your wrangled data
-   Reporting on 1) your data wrangling efforts and 2) your data analyses and visualizations

### Gathering Data for this Project

Gather each of the three pieces of data as described below in a Jupyter Notebook titled  `wrangle_act.ipynb`:

1.  The WeRateDogs Twitter archive. I am giving this file to you, so imagine it as a file on hand. Download this file manually by clicking the following link:  [`twitter_archive_enhanced.csv`](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced.csv)
    
2.  The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (`image_predictions.tsv`) is hosted on Udacity's servers and should be downloaded programmatically using the  [Requests](http://docs.python-requests.org/en/master/)  library and the following URL:  [https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv)
    
3.  Each tweet's retweet count and favorite ("like") count at minimum, and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's  [Tweepy](http://www.tweepy.org/)  library and store each tweet's entire set of JSON data in a file called  `tweet_json.txt`  file. Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count.  _Note: do not include your Twitter API keys, secrets, and tokens in your project submission._
    

If you decide to complete your project in the Project Workspace, note that you can upload files to the Jupyter Notebook Workspace by clicking the "Upload" button in the top righthand corner of the dashboard.

[](https://classroom.udacity.com/nanodegrees/nd002/parts/af503f34-9646-4795-a916-190ebc82cb4a/modules/14d9f5f1-9e7b-4bfb-97f3-bcdbf4a3699c/lessons/a8085857-3e28-4fc7-aeb8-da64ccbc2e20/concepts/5919f3b1-899f-4295-80f1-17f091eb4df6#)

![Jupyter Notebook dashboard with arrow pointing to the "Upload" button](https://video.udacity-data.com/topher/2017/October/59f40494_screenshot-2017-10-28-00.14.26/screenshot-2017-10-28-00.14.26.png)

_Jupyter Notebook dashboard with arrow pointing to the "Upload" button_

### Assessing Data for this Project

After gathering each of the above pieces of data, assess them visually and programmatically for quality and tidiness issues. Detect and document at least  **eight (8) quality issues**  and  **two (2) tidiness issues**in your  `wrangle_act.ipynb`  Jupyter Notebook. To meet specifications, the issues that satisfy the Project Motivation (see the  _Key Points_  header on the previous page) must be assessed.

### Cleaning Data for this Project

Clean each of the issues you documented while assessing. Perform this cleaning in  `wrangle_act.ipynb`as well. The result should be a high quality and tidy master pandas DataFrame (or DataFrames, if appropriate). Again, the issues that satisfy the Project Motivation must be cleaned.

### Storing, Analyzing, and Visualizing Data for this Project

Store the clean DataFrame(s) in a CSV file with the main one named  `twitter_archive_master.csv`. If additional files exist because multiple tables are required for tidiness, name these files appropriately. Additionally, you may store the cleaned data in a SQLite database (which is to be submitted as well if you do).

Analyze and visualize your wrangled data in your  `wrangle_act.ipynb`  Jupyter Notebook. At least  **three (3) insights and one (1) visualization**  must be produced.

### Reporting for this Project

Create a  **300-600 word written report**  called  `wrangle_report.pdf`  or  `wrangle_report.html`  that briefly describes your wrangling efforts. This is to be framed as an internal document.

Create a  **250-word-minimum written report**  called  `act_report.pdf`  or  `act_report.html`  that communicates the insights and displays the visualization(s) produced from your wrangled data. This is to be framed as an external document, like a blog post or magazine article, for example.

Both of these documents can be created in separate Jupyter Notebooks using the  [Markdown functionality](http://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html)  of Jupyter Notebooks, then downloading those notebooks as PDF files or HTML files (see image below). You might prefer to use a word processor like Google Docs or Microsoft Word, however.

[](https://classroom.udacity.com/nanodegrees/nd002/parts/af503f34-9646-4795-a916-190ebc82cb4a/modules/14d9f5f1-9e7b-4bfb-97f3-bcdbf4a3699c/lessons/a8085857-3e28-4fc7-aeb8-da64ccbc2e20/concepts/5919f3b1-899f-4295-80f1-17f091eb4df6#)

![*Download Jupyter Notebook in PDF form*](https://video.udacity-data.com/topher/2017/October/59f4084b_screenshot-2017-10-28-00.29.25/screenshot-2017-10-28-00.29.25.png)

_Download Jupyter Notebook in PDF form_
