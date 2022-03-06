This assignment was the twitter_coronavirus assignment for our Big Data class cmc-csci143, completed on Mar 5, 2022. This repo was forked from https://github.com/mikeizbicki/twitter_coronavirus/tree/51e77e53a10aa2933e29378883051464357095f9.

For this assignment, I ran `map.py` on each of the tweet zip files in `/data/tweets_corona` using the script `src/run_map.sh`. This step mapped the usage of the common covid hashtags by language and by country. Then I reduced the output to two files using `reduce.py`. Finally, using the `src/run_visualize.sh` script, I ran the `visualize.py` on the reduced language and country files for each common covid hashtag. This produced outputs in the `viz` directory which mapped the number of occurences of each hashtag by language or country. 
