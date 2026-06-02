# SetTop Insight AI

## Television Consumption, Viewer Engagement, Subscription Intelligence and Churn Risk Analytics Platform

---

## Overview

SetTop Insight AI is a television consumption intelligence platform designed to analyze viewer behavior, channel loyalty, viewing patterns, subscription value, service quality, and customer retention using set-top box data.

The project transforms raw television viewing data into meaningful business insights that can help broadcasters, DTH operators, cable providers, and media companies understand customer behavior and improve viewer engagement.

---

## Problem Statement

Television operators collect large amounts of viewing data every day.

However, they often struggle to answer questions such as:

- Which channels retain viewers the longest?
- Why do viewers switch channels frequently?
- Which customers are likely to discontinue their subscriptions?
- Which subscription plans provide the highest value?
- What genres are most popular?
- Which districts have the highest engagement?
- How do advertisements impact viewer behavior?

SetTop Insight AI addresses these challenges through advanced analytics and intelligent viewer profiling.

---

## Objectives

The primary objectives of this project are:

- Analyze television viewing behavior.
- Measure viewer engagement.
- Evaluate channel loyalty.
- Assess subscription value.
- Identify churn risks.
- Analyze service quality issues.
- Generate business intelligence insights.
- Recommend actions to improve customer retention.

---

## Key Features

### Viewer Attention Analysis

Measures how engaged viewers are with television content.

Factors considered:

- Watch Duration
- Channel Switching Frequency
- Viewing Patterns

---

### Channel Loyalty Index

Measures viewer loyalty toward channels.

Higher scores indicate:

- Consistent viewing behavior
- Reduced channel switching
- Higher audience retention

---

### Engagement Score

Combines:

- Viewer Attention
- Channel Loyalty
- Subscription Value

to measure overall customer engagement.

---

### Advertisement Impact Analysis

Evaluates:

- Advertisement Frequency
- Channel Switching Behavior
- Potential Advertisement Exit Risk

---

### Subscription Intelligence

Analyzes:

- Subscription Plans
- Viewing Habits
- Subscription Value

to determine whether customers are receiving value from their packages.

---

### Churn Risk Analysis

Identifies customers who may discontinue services.

Factors include:

- Low Engagement
- Low Loyalty
- Service Complaints
- Reduced Viewing Activity

---

### Service Quality Analytics

Measures:

- Signal Strength
- Service Complaints
- Viewing Experience

to evaluate customer satisfaction.

---

## Dataset Information

Dataset Name

```text
SetTop_Insight_AI_Master_Dataset.csv
```

---

## Dataset Features

| Feature | Description |
|----------|-------------|
| CustomerID | Unique Customer Identifier |
| District | Customer Location |
| AgeGroup | Customer Age Category |
| Gender | Customer Gender |
| SubscriptionPlan | Current Subscription Package |
| ChannelName | Channel Viewed |
| Genre | Content Genre |
| ViewingTimeSlot | Viewing Time Period |
| WatchDurationMinutes | Viewing Duration |
| ChannelSwitches | Number of Channel Changes |
| AdvertisementCount | Number of Advertisements |
| SignalStrength | Service Signal Quality |
| ServiceComplaints | Customer Complaints |
| ChannelLoyaltyIndex | Loyalty Score |
| ViewerAttentionScore | Viewer Engagement Score |
| SubscriptionValueScore | Package Value Score |
| InternetUsageLevel | Internet Consumption Level |
| ViewingDayType | Weekday or Weekend |
| RegionType | Urban, Semi-Urban, or Rural |

---

## Feature Engineering

The project generates additional business intelligence metrics.

### Engagement Score

Measures overall customer engagement.

---

### Advertisement Exit Risk Score

Measures the likelihood of viewers leaving content due to advertisements.

---

### Churn Risk Score

Estimates the probability of customer churn.

---

### Retention Score

Measures customer retention strength.

---

### Premium Upgrade Probability

Identifies customers likely to upgrade subscription plans.

---

## Analytics Dashboard

The platform generates multiple visualizations.

### Average Watch Time by Channel

Identifies the most engaging channels.

---

### Genre Popularity Analysis

Shows content preferences across viewers.

---

### Viewer Attention Distribution

Analyzes engagement levels.

---

### Channel Loyalty Distribution

Measures audience retention.

---

### Subscription Value Analysis

Compares subscription package effectiveness.

---

### District-wise Viewing Analysis

Identifies geographical viewing trends.

---

### Churn Risk Analysis

Highlights customer retention challenges.

---

### Correlation Matrix

Examines relationships between important business metrics.

---

## Workflow

### Step 1

Load television consumption dataset.

---

### Step 2

Perform data validation and quality checks.

---

### Step 3

Generate business intelligence metrics.

---

### Step 4

Create viewer engagement analytics.

---

### Step 5

Analyze subscription performance.

---

### Step 6

Generate churn risk indicators.

---

### Step 7

Collect user input.

---

### Step 8

Generate personalized viewer intelligence reports.

---

## Interactive Viewer Analyzer

The system accepts:

```text
Average Watch Time
Channel Switches
Subscription Plan
Favourite Genre
Service Complaints
```

and generates:

```text
Viewer Attention Score
Loyalty Score
Engagement Score
Subscription Value Score
Churn Risk Score
```

---

## Example Input

```text
Average Daily Watch Time: 180

Channel Switches: 5

Subscription Plan: Family

Favourite Genre: Movies

Service Complaints: 2
```

---

## Example Output

```text
Attention Score: 52.5

Loyalty Score: 90

Engagement Score: 70.75

Churn Risk Score: 25.0

Subscription Value Score: 66.4
```

---

## Smart Recommendation Engine

Provides recommendations regarding:

- Subscription Optimization
- Churn Prevention
- Content Preferences
- Upgrade Opportunities
- Customer Retention Strategies

---

## Technologies Used

### Programming Language

- Python

### Data Analysis

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn

### Development Environment

- Google Colab

### Version Control

- GitHub

---

## Project Structure

```text
SetTop-Insight-AI/
│
├── data/
│   └── SetTop_Insight_AI_Master_Dataset.csv
│
├── notebooks/
│   └── SetTop_Insight_AI_Television_Consumption_Intelligence_System.ipynb
│
├── charts/
│
├── reports/
│
├── assets/
│
├── README.md
│
├── requirements.txt
│
├── LICENSE
│
└── .gitignore
```

---

## Business Impact

### For DTH Operators

- Improve customer retention.
- Reduce subscriber churn.
- Optimize subscription packages.

---

### For Broadcasters

- Understand viewer behavior.
- Measure channel loyalty.
- Improve content strategy.

---

### For Advertisers

- Measure advertisement effectiveness.
- Analyze viewer engagement patterns.

---

### For Media Companies

- Generate actionable business intelligence.
- Improve customer experience.

---

## Future Enhancements

### Machine Learning Churn Prediction

Predict customer churn using classification models.

---

### Personalized Content Recommendation Engine

Recommend channels and programs.

---

### Real-Time Viewing Analytics

Analyze streaming behavior in real time.

---

### Customer Lifetime Value Prediction

Estimate long-term subscriber value.

---

### Advertisement Optimization Engine

Improve advertisement targeting.

---

### OTT Platform Integration

Combine television and OTT analytics.

---

## Expected Outcomes

SetTop Insight AI helps organizations:

- Understand viewer behavior.
- Increase customer retention.
- Improve subscription value.
- Reduce churn.
- Enhance content strategy.
- Optimize business decisions.

---

## Author

Bhashyam Sree Darshan

---

## License

This project is intended for educational, analytical, and research purposes.
