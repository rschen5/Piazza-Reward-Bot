# Piazza Reward Bot

Piazza is a popular platform that facilitates discussion between students and professors in a forum format. However, it does not provide very detailed statistics on student participation (e.g. number of questions posted and answered, upvotes), especially for large (> 25) classes. This bot reports personalized statistics and converts them into points as specified by the instructor. Students can track their own participation on the forum and compare their activity level to the most active students in the class. Instructors can use the bot to incentive students to participate more on Piazza.

For this bot, I implemented a scraper to collect and parse data from a Piazza forum, calculate participation points for each student, and update the points in a MongoDB database. I worked with an unofficial Piazza API, the pymongo package in Python, and MongoDB. I worked with my teammates to integrate the scraper with the Discord bot commands and did some preliminary testing of the commands.

Languages and tools used:
* Node.js
* Python ([pymongo](https://pypi.org/project/pymongo))
* MongoDB
* [Unofficial Piazza API](https://github.com/hfaran/piazza-api)

Since this is a school project, the code cannot be shared. However, here is a demo of how the bot works. Please see the report and slides for further detail.
