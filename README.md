# PROJECT-2: Data Modeling with Cassandra



## Overview

The goal of this project is to create a Cassandra database built around an event file in order to answer 3 types of questions:
* Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
* Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
* Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'
