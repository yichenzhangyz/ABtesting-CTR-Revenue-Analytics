# ABtesting-CTR-Revenue-Analytics
This is showing how I did data analytics on A/B testing results.

The dataset sample I have have following columns userid|country|groups|deviceid|device|sellerid|itemid|date|views|clicks|revenue

The notebook includes following topics -
1. Check problems in dataset (missing userid, mixed users, users with multi devices, devices with multi-users)
2. Deep dive into problems by country/devices to find potential root cause
3. Analyze A/B testing results with one of metrics - CTR, excluding progblematic records
4. Analyze A/B testing results with one of metrics - Revenue, excluding progblematic records
5. Results analysis
6. Cohort analysis
