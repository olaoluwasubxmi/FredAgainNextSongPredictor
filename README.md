# FredAgainNextSongPredictor

# Introduction
Fred John Philip Gibson, known professionally as Fred Again or simply Fred, is a British record producer,
singer, songwriter, multi-instrumentalist, and DJ.
Ideology: I was casually scrolling on Youtube As I always do when I'm eating and came across this Gem
called FredAgain and he was doing a live performance for the boiler room. And I know Boiler room
videos are always 1 hr plus and this was the first boiler room video I can say I watched from the
beginning to the end and my conclusion thoughts were just...”Wow” So immediately I started to listen
to more of his songs, Follow him on social media, and listen to previous and present works of his. So a
day came by and I saw he posted on his Instagram 3 Samples of his soon-to-come album and asked in
the caption Which does he want us to drop first between 1,2 and 3 of the samples he provided on the
post and me being the Data Scientist I am... I told myself I would Predict what song is he going to release
next with the help of programming
With the aid of a tool called Phantom Buster and my personal Instagram session cookie, I was able to
scrape 700 of the post's 15,9k comments as the first thing I did. (Yes, I agree.)
I transferred them from the CSV format they were in into an excel spreadsheet. and the data that was
gathered appeared somewhat like the attached image below
The most important on the table would be username, comment, and likecount
As we can see from the table, the comment column contains a lot of unfiltered data, such as Latin letters,
the letter!, and other content that is not what we want.
I made the decision to solely use the data from the original question he asked—"Pick amongst 1, 2, and
3"—for this project. I therefore cleaned the data so that it only displayed the numbers 1, 2, and 3, and in
order to improve this project in the future, I would like to suggest that the likecount be given some sort
of weight as not everyone would want to comment instead of just like what they want.
In order to determine which song Fredagain would release next based on the comment data, I cleaned
the comments so that they only contained the numbers 1, 2, and 3. The computer then calculated how
many 1s, 2s, and 3s were in the data and created a graph for the entire project.
The good thing about this project is that it can be modified to anything different because it can be used
for voting, polls, and so many other things in addition to Instagram comments from artists.
