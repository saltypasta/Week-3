# Voyant

- Text analysis in a nutshell:
  - collect texts because you have an idea
    - look for patterns
  - Find Relationships
  - interpret the meaning of what you find
  - make the argument for the wider significance

- Voyant allows us to visualize and analyze text in lots of ways that would be incredibly tedious to do manually. The ability to sort the text in various ways quickly allows us to look for new patterns and relationships. Voyant makes it easy to *play* with the different visualizations, and is thus reffered to as a the **gateway drug** to the digital humanities

- Corpus Id is https://voyant-tools.org/?corpus=49f48aa297f23faaecb77e664a9f0650
- Using the terms table in the top left, we can select or search for terms througout the data and view the frequency over time visualized in a spark graph in the top right. **IMPORTANT** The spark graph works because we have our data sorted *Chronologically*. If our data was sorted differently, this graph would have a different meaning. Additionally, depending on how our curation methods for the data this graph could be effected
- click on the points in the graph in the top right to look closely at the texts that form that data point. the texts appear in the bottom right under the contexts tab
- Can filter out words we dont want to see with the "options" tool in the top right of the word cloud panel
- I tried searching for "Penitentiary" in the data and found nothing. I did find a correlation between the term "justice" and "Kingston" in the late 1820s and 1830s, which is consistent with the Kingston penitentiary being built in 1835 following the adoption of Peel's consolidations to Upper Canada's criminal law system in 1833. I have learned about these events from classes and journal articles, however it is extremely valuable to be able to visualize this with data and switch between a macro "scholarly" perspective and a micro perspective of specific events transpiring in this period
- Patterns are dope.

- Key takeaways:
  - Voyant is useful for visualizing patterns and relationships in text data
  - As usual, it's important to keep in mind how your methods of arriving to these insights can influence the insights themselves. in other words, be mindful of what you are manipulating and what that might mean beyond your initial ideas.

# Twine

- Played the depression game [here](http://www.depressionquest.com/)
  - That hits hard. In a good way. This is a good resource to keep in mind for some of my friends
- the game’s argument?
  - Sufferers of depression are not alone. For those that do not suffer from depression, it is not as simple as feeling sad. Sufferers of depression are aware of how they may appear to others (lazy, unmotivated, antisocial) and this only serves to worsen their condition through negative feedback loops.

- the way the design of the experience contributes to that argument?
  - the inclusion and blocking off of the choices a player would naturally wish to make to improve their situation is a powerful representation of how depression acts upon the victims mind. It illustrates the conscientiousness of sufferers of depression while also showing the impossibility of choosing the "right" thing.
  - the meters on the bottom of the game tracking your level of depression, therapy, and medication are effective in portraying how your decisions impact these factors. This is not the most realistic way to portray it however, as often sufferers of depression are not aware they are suffering to begin with, or that they are getting "better" or "worse". The game does acknowledge this in advance, as well as within the game.

- who is the intended audience?
  - Sufferers of depression as well as those who perhaps lack a practical understanding of how depression intersects with day to day life. Both audiences can benefit greatly from playing this game while reflecting on their own life experiences (providing they are in a secure state of mind before playing).

- Making my own history text game sounds like a lot of fun, but I dont quite have the time at the moment. Going to try out Antconc instead, but keep this in mind for the final project and the future!

# Antconc

- Tabs accross the top are:

  - Concordance: This will show you what’s known as a Keyword in Context view
  - Concordance Plot: This will show you a very simple visualization of your KWIC search, where each instance will be represented as a little black line from beginning to end of each file containing the search term
  - File View: This will show you a full file view for larger context of a result.
  - Collocates: collocates show words which are statistically likely to appear together
  - Word list: All the words in your corpus
  - Keyword List: This will show comparisons between two corpora

- The corpus of chapbooks we are using is very large, so when searching for terms it takes quite a while to process every file. To save time, if its not necessary to use the entire corpus it may be worth filtering out some of the chapbooks using the metadata and asking questions. ex. if the patterns you are looking for only apply to a specific date range, you can choose to only use data from within those dates.
  - this would also make for more accurate analysis
-  Im going to select a just a few files to use for the rest of the analysis. Using 3000+ files is making it very slow to process, and my search's are pulling up a lot of weird things like this "A A.A M-J A A. A A". Im sure this has some reason for being there, but its hard to deduce when looking at thousands of instances of it occurring. (Ties in to micro vs macro perspectives)
- took a random chunk of these files and made a new directory, then loaded these into Antconc
- Use the Kwick sort at the bottom to adjust how many words appear to the left and right of your keyword
- Use an * to find your keyword ending with 0 or more characters. Ex. Searching for King* can yield King's, Kings, Kingston, Kingdom etc.
- Use ? to do a similar search, for a single character. ex. Th?n may yield Then, than etc. where as Th*n may yield thrown, thorn, etc. in addition to the reults of Th?n
- Did the wom?n vs m?n search and wow. 29 hits for wom?n and 299 hits for m?n. I selected this data randomly, and "man" could be used to describe humanity as a whole in some contexts, but I would say it looks probable that men are written about more in these chapbooks. to further explore this i would use more chapbooks, and have a look at the Collocates to see what themes might be present around Men and Women in these chapbooks.
- oh lol thats the next step in the tutorial
- there were several collocates after searching "She" that were negative things such as wretchedness, yelpin', threatens etc. many of these also appeared as collocates for "he" aswell. After clicking on some to look in context, many of these were not applying to the "he" or "she" in question, but were simply correlated as they were in the same sentence. *context is very important*
- loaded in the original corpus as a reference corpus for the one I randomly compiled
- Using key-ness, we can evaluate whether a key work occurs more or less often than would be expected by chance in comparison to the reference Corpus
- in my example, I can compare my two compora to determine if the keywords present in my reference corpus are consistent with the original collection of chapbooks or if the files I have selected have different probabilities of these keywords occurring

- Key takeaways:
  - Antconc is a powerful text analysis tool that allows us to make comparisons on a large scale. These comparisons can be used to ask meaningful questions, and in some cases answer them
  - Context is key. Looking at large patterns can be insightful as long as the data is not taken out of context

# Story maps

- Really intuitive tool for mapping out stories with geographical narratives
- I made a quick and dirty storymap of Jacques Cartier's three main voyages, and used the info on History.com to fill the slides

Key takeaways:
- Great tool for visualizing the location aspect of stories. Lots of opportunities to add media to capture the viewers attention
- Easy to make an accessible presentation that is easily shared or embedded 
