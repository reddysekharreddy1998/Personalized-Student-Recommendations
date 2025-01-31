# Personalized-Student-Recommendations
Overview

This project analyzes quiz performance data to provide insights, recommendations, and a predictive model for estimating NEET ranks based on historical quiz scores. The system fetches quiz, submission, and historical data from API endpoints, processes the data, and generates recommendations for improvement. Additionally, it visualizes performance trends and uses a linear regression model to predict NEET ranks.

Features

Quiz Data Analysis: Extracts and summarizes key quiz details.

Submission Performance Analysis: Evaluates the user's accuracy and score distribution.

Historical Performance Insights: Analyzes past quiz performance trends.

Recommendations System: Suggests improvement areas based on weak topics.

NEET Rank Prediction: Uses a linear regression model to estimate future performance.

Data Visualization: Displays performance trends over time.

Setup Instructions

Prerequisites

Ensure you have Python installed (>= 3.7) and install the required dependencies:


Approach

Data Collection

The project retrieves data from three API endpoints:

Quiz Data: Contains quiz metadata, duration, number of questions, and scoring details.

Submission Data: Stores user-specific performance metrics such as score, accuracy, and response mapping.

Historical Quiz Data: Maintains records of past quiz scores for trend analysis.

Data Processing & Analysis

Extracts relevant fields from JSON responses.

Summarizes quiz structure and identifies key topics.

Analyzes user performance and identifies strengths/weaknesses.

Computes historical accuracy and score trends.

Prediction Model

Uses Linear Regression to predict the user’s future NEET rank.

Trains on past scores and evaluates performance on the latest quiz.

Visualization

Plots score trends and accuracy rates over time using Matplotlib.

Output

Performance insights and topic-wise recommendations.

Estimated NEET rank based on historical quiz data.

Graphical representation of quiz performance trends.

Future Improvements

Enhance prediction accuracy with more advanced ML models.

Implement interactive dashboards for better visualization.

Expand dataset with additional quiz parameters for deeper insights.

