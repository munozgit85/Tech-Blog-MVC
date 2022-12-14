# Tech-Blog-MVC

## Description

-AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments

## Table of Contents

- [Installation](#Installation)
- [Usage](#Usage)
- [Screenshot](#Screenshot)
- [License](#license)
- [Contributing](#Contributing)
- [Tests](#Tests)
- [Github/URL](#Github)
- [Questions](#Questions)

---

## Installation

1. install npm by typing in command line npm init, then npm install
2. install MYSQL2 https://www.npmjs.com/package/mysql2
3. install Sequelize https://www.npmjs.com/package/sequelize
4. install dotenv https://www.npmjs.com/package/dotenv
5. install express-handlebars https://www.npmjs.com/package/express-handlebars
6. install bcrypt packagenhttps://www.npmjs.com/package/bcrypt
7. install express-session https://www.npmjs.com/package/express-session
8. install connect-session-sequelize https://www.npmjs.com/package/connect-session-sequelize

## Usage

- First clone the repository from GitHub.
- Complete the necessary installation, in the installation tab.
- Complete appropriate username and password for the user account for SQL is input into
  .env file.
- Then, run mysql -u root -p and enter your password, to start SQL.
- Then, type in USE database tech_blog_mvc_db;
- Then type in source db/schema.sql at root of the application.
- Type quit to log out of SQL
- Finally, connect to the server and run npm start.

  ## Screenshot

  <img width="1403" alt="tech screenshort" src="https://user-images.githubusercontent.com/107218022/196593323-4f77c728-7473-42de-abb8-6af46747529f.png">

  <img width="1348" alt="2nd screen shot" src="https://user-images.githubusercontent.com/107218022/196593430-500fe4c9-737f-4897-b5b1-f6c3fdd8236d.png">

  ## License

  No license.

  ## Contributing

  none

  ## Test

  none

## Github

https://github.com/munozgit85/Tech-Blog-MVC.git
https://afternoon-woodland-47600.herokuapp.com
https://munozgit85.github.io/Tech-Blog-MVC/

## Questions

For further Questions About This Application , Please Feel Free To Use The Contact Below:

> Email: Racquelg85@hotmail.com
> GitHub : [Racquel](https://github.com/munozgit85/Tech-Blog-MVC.git)
