# DataEngineerChallenge_1

## ReadLogSpark.scala : Spark implementation for parsing weblogs, this task achieves below goals.
・ Part 1 : Sessionize the web log by IP. Sessionize = aggregrate all page hits by visitor/IP during a fixed time window. 
・ Part 2: Determine the average session time 
・ Part 3: Determine unique URL visits per session. To clarify, count a hit to a unique URL only once per session. 
・ Part 4: Find the most engaged users, ie the IPs with the longest session times Session window time is chosen to be 15 minutes.
