# Dezzer_API
Beginners guide to Dezzer free API services


Dezzer API allows you to use some of the API services free of charge. 
I felt that the explanation given by Dezzer API website was not detailed enough and helpful, So I wrote this to help others like me.

Dezzer don't require the use of a personal key for scraping general data (but you can't collect data on users).
You can use the API key in order to collect data on your personal account.  

The code I wrote was designed to pull the song names of select artists from Dezzer.
For my explanation I downloaded a list of 100 artists from another website and turned it into CSV. 
The code is getting the top tracks (first 100 songs of every artist) into a dictunary. 

Thanks to Nikita Kholin for the idea to perss the "next" button.
KholinLabs- @hmlON

Link to Dezzer website: https://www.deezer.com/
Link to Dezzer API service: https://developers.deezer.com/api


#Key notes to understand the code:

Artist dict = {"song list":[list of top songs],"how many songs":"num","time to run the code for the artist":"time"}

All artist dict = {"name of the artist":"Artist dict"}

space in url = %20
