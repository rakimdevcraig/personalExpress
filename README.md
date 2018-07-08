## Installation

1. Clone repo
2. run `npm install`

## Usage

1. run `node server.js`
2. Navigate to `localhost:7000`

Who Should Lebron James sign to?

This project gives a chance to all fans of Lebron James to state what team he should sign to and why. I will show Lebron
the results before he decides his next team.

![pic](pic.jpg)

Link to project:

How It's Made:
Tech used: HTML, CSS, Javascript, Node, Express, Mongo, Embedded Javascript

I started off by using Node and Express to create a server that my browser can connect to. After ensuring my server was up and running I created a form in Embedded Javascript that the user can input info to. After that I linked my Mongo database to the form so when information gets entered it also gets stored into the database. I then added 2 pictures of Lebron that allows the user to vote on the post, one with him giving a thumbs up and the other with him giving
disapproval. All of these results are logged to the database so I can show Lebron.

Optimizations:
Instead of having a simple thumbs up and thumbs down button I wanted to use pictures of Lebron that could represent what the user felt so I found those 2 pictures and used those instead of a thumbs up and down button.

Lessons Learned: I created an express server, learned to execute CRUD operations, save and read from MongoDB and I also learned to use a template engine like Embedded JS. I also learned how to tie a click event of a picture to a vote count.

Examples:
Take a look at these couple examples that I have in my own portfolio:
