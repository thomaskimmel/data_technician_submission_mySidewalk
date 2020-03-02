# data_technician_submission_mySidewalk

I created the table by downloading the dataset from the San Francisco Open Data Portal, reformatting the datetimes of the relevant columns (Call Date, Received DtTm, On Scene DtTm), filtering the results to only the past 12 months, calculating the difference between the On Scene datetimes and Call Received datetimes in seconds, grouping by Battalion and Month, calculating the top decile of response times (the response times in the top 90th percentile), renamed and reordered the columns to be consistent with the provided example, and exported as a csv.

Python and R make this type of data manipulation relatively easy.  It is crucial to think about reproducibility when organizing and manipulating data.  Scripting commonly executed tasks can maximize efficiency.  Well-organized data in a clear workflow is invaluable for effective data science workflows.  
