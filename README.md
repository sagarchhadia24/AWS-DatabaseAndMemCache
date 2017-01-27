# AWS-DatabaseAndMemCache

Get access to AWS (Amazon Cloud).
2. Find a large dataset (50K tuples or larger)
http://earthquake.usgs.gov/earthquakes/feed/v1.0/csv.php (test, small)
https://www.data.gov/ (many here, for example vehicle recalls)
3. Copy that file to AWS, and time (instrument) how much time it takes.
4. Put the data into a Relational DB. (time)
5. Write the code to do one thousand, 5 thousand and 20 thousand random
(small) queries. (time)
6. Repeat using queries of only 200 to 800 tuples.
7. Repeat previous two steps using “Elastic” Cache (Memcache, etc.)
8. Display your results on console.
Web Services
