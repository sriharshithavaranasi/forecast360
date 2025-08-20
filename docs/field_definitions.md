# Account Custom Fields (Forecast360)

| Field API Name                  | Label                        | Type     | Description |
|---------------------------------|------------------------------|----------|-------------|
| Ext_Account_ID__c               | External Account ID          | Text     | Unique external ID to map Slack/Usage data |
| NPS_Score__c                    | NPS Score                    | Number   | Net Promoter Score (customer loyalty) |
| Feature_Usage_Hours_14d__c      | Feature Usage Hours (14d)    | Number   | Total hours of product usage in past 14 days |
| Logins_14d__c                   | Logins (14d)                 | Number   | Number of logins in past 14 days |
| Usage_Drop_Pct_14d__c           | Usage Drop % (14d)           | Percent  | Decline in usage compared to prior period |
| Open_Tickets_14d__c             | Open Tickets (14d)           | Number   | Support tickets opened in last 14 days |
| Avg_Slack_Sentiment_14d__c      | Avg Slack Sentiment (14d)    | Number   | Average sentiment of Slack support mentions (-1 to 1) |
| Churned_Last_60d__c             | Churned Last 60d             | Checkbox | Labeled churn outcome (used for training Einstein) |
