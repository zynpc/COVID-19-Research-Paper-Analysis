# COVID-19-Research-Paper-Analysis

This project explores global research activity surrounding COVID-19 by analyzing a dataset of academic publications. The aim is to understand how the scientific community responded to the pandemic in terms of publication volume, technical focus, and emotional tone.

## Goals

- Track the increase in COVID-19 research across years.
- Identify the most prolific authors and journals.
- Compare publication types (preprint vs peer-reviewed).
- Extract important technical terms from abstracts using TF-IDF.
- Analyze the sentiment of research abstracts.

## Methods Used:
- Data Cleaning: Removed duplicates, missing values, and standardized formats.
- Trend Analysis: Analyzed the yearly count of publications to observe how COVID-19 research output evolved over time.
- Exploratory Statistics: Identified the top 10 most common journals by publication count and highlighted the most prolific authors contributing to the research.
- Publication Type Classification: Categorized papers into Preprints and Journal articles based on the source_x field to analyze distribution and publication patterns.
- TF-IDF Analysis: Extracted significant domain-specific terms.
- Sentiment Analysis: Applied polarity scoring to abstracts using TextBlob.

## Technologies

- Python
- Pandas, Matplotlib, Seaborn
- Scikit-learn (TF-IDF)
- TextBlob (Sentiment Analysis)

## Summary:
This multi-angle analysis provides insights into how the scientific community responded to COVID-19, both in terms of quantity and content. We observe a sharp increase in research activity post-2020, with key journals and authors emerging as major contributors. TF-IDF revealed dominant terminology related to virology and medicine, while sentiment analysis suggested a generally neutral and positive tone, with variations based on topic and year.

This notebook combines classical statistical techniques with NLP to offer a comprehensive picture of COVID-19 scholarly communication.

