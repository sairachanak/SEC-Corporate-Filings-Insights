SEC Corporate Filings Insights
Project Overview
This project analyzes SEC financial filings to extract insights on corporate financial health, executive networks, and reporting anomalies. Using graph analytics, machine learning clustering, and GraphRAG, the system processes millions of financial records from 5,000+ public companies to provide comprehensive financial intelligence.
Course: Applied Big Data Analytics - GWU
Dataset: SEC Financial Statement Data Set (XBRL filings)
Time Period: 2012-2016 (assigned year-based allocation)

Key Features
1. Financial Statement Analysis

Comparative analysis of revenue, income, debt, assets, and liabilities across companies
Benchmarking and performance evaluation using standardized financial metrics
Calculation of key ratios (Asset-to-Liability, Debt-to-Income)

2. Company Financial Health Clustering

Unsupervised ML clustering (K-means) to segment companies into risk tiers
Classification based on revenue, debt, and other financial indicators
Achieved 0.78 silhouette score with 4 distinct clusters

3. Anomaly Detection

Identification of unusual reporting patterns and significant deviations
Detection of potential fraud or misrepresentation indicators
12% anomaly detection rate across analyzed filings

4. Executive Network Analysis

Graph-based analysis of corporate executives and board members
Centrality analysis to identify influential leaders across companies
Extracted 15,000+ executive relationships from 10-K filings
Web scraping of signature sections to build connection maps

5. GraphRAG Query System

Natural language interface for querying financial metrics and trends
Plain English queries for complex financial insights
Powered by graph database relationships and RAG architecture


Dataset Structure
The SEC Financial Statement Data Set consists of four components:
SUB (Submission Data)

Metadata about each XBRL submission
Filing entity information
Submission dates and form types

NUM (Number Data)

Individual numeric values from financial statements
Line items from Balance Sheet, Income Statement, Cash Flow, etc.
10M+ financial data points processed

TAG (Tag Data)

Metadata about XBRL tags
Taxonomy versions and documentation labels
Tag attributes and definitions

PRE (Presentation Data)

Tag presentation structure
Sequence and hierarchy of financial statement items


