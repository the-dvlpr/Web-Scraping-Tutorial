# Web Scraping/Crawling Tutorial
A tutorial on web scraping and crawling aimed to get you up and running in 15 minutes.

### YouTube Videos
<a href="http://www.youtube.com/watch?feature=player_embedded&v=cswubkLlocI" target="\_blank"><img src="http://img.youtube.com/vi/cswubkLlocI/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10"/></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=Bh4gy602NTs" target="\_blank"><img src="http://img.youtube.com/vi/Bh4gy602NTs/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10"/></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=f8WQZNbHHX8" target="\_blank"><img src="http://img.youtube.com/vi/f8WQZNbHHX8/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10"/></a>

### Credentials
Make sure to update your login info in the credentials.rb file.

### How to Run from Command Line
To run each file navigate to the main directory (web_scraper) in your terminal and run the word `ruby` followed by the name of the file. Example:
`$ ruby auto_follow.rb`
or
`$ ruby auto_liker.rb`

### UPDATES (since videos were made)
I've made some fairly simple updates since the videos.
- changed the ```while true``` loops to `loop do` loops with a break condition using a constant variable set at top
- added more variables for counting, tracking, and info output
- added top 100 users on instagram at the bottom of `auto_follow.rb`

### Libraries Used
[watir](https://github.com/watir/watir) for crawling in live browser<br>
[pry](https://github.com/pry/pry) ruby REPL<br>
[rb-readline](https://github.com/ConnorAtherton/rb-readline) ruby IRB and dependency of pry<br>
[awesome-print](https://github.com/awesome-print/awesome_print) for clearer console output
