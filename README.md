# mjokipro

An application used to display course projects for Matthew Joki, built with React, Express, and Postgresql.

![image](https://github.com/mjokipro/mjpro-fe/assets/132299821/f61d6b2d-dd92-41b9-830a-3839259241fd)


# Installation and Setup Instructions

Clone down this repository. You will need node and npm installed globally on your machine.

## Installation:

npm install

## To Run Test Suite:

npm test

## To Start Server:

npm start

## To Visit App:

localhost:3000/

# Reflection
The drive for this project was to create an inovative capstone final project, and a personal portfolio site listing more projects, for the Software Engineering at Auburn University.
I set out to build only a basic CRUD app.
This project was challenging because it provided the opportunity to gain experience using this new skill.
An unexpected obsticle that I encountered was during deployment.  I must have too many free Surge sites, and secure login posed a problem, so I moved to Render.com.
I used React, Express, and PostgreSQL to complete this project.

Example:
This was a week long project built during my third module at Auburn. Project goals included using technologies learned up until this point and familiarizing myself with documentation for new features.

Originally I wanted to build an application that allowed users to pull data from the Twitter API based on what they were interested in, such as 'most tagged users'. I started this process by using the create-react-app boilerplate, then adding react-router-4.0 and redux.

One of the main challenges I ran into was Authentication. This lead me to spend a few days on a research spike into OAuth, Auth0, and two-factor authentication using Firebase or other third parties. Due to project time constraints, I had to table authentication and focus more on data visualization from parts of the API that weren't restricted to authenticated users.

At the end of the day, the technologies implemented in this project are React, React-Router 4.0, Redux, LoDash, D3, and a significant amount of VanillaJS, JSX, and CSS. I chose to use the create-react-app boilerplate to minimize initial setup and invest more time in diving into weird technological rabbit holes. In the next iteration I plan on handrolling a webpack.config.js file to more fully understand the build process.
