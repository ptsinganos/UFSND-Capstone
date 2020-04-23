# Udacity Full Stack Nanodegree Capstone Project

The Casting Agency models a company that is responsible for creating movies and managing and assigning actors to those movies. You are an Executive Producer within the company and are creating a system to simplify and streamline your process.

The frontend app (developed with create-ract-app) is hosted on heroku https://ufsnd-casting-agency-frontend.herokuapp.com/. Details about hosting locally and deploying on heroku are provided in `/frontend/README.md`

The backend api (developed with flask) is hosted on heroku https://ufsnd-casting-agency-backend.herokuapp.com/. Access to the api requires authorization. To that effect three roles have been configured in Auth0:
- Casting Assistant
  - Can view actors and movies
- Casting Director
  - All permissions a Casting Assistant has and…
  - Add or delete an actor from the database
  - Modify actors or movies
- Executive Producer
  - All permissions a Casting Director has and…
  - Add or delete a movie from the database
Details about the endpoints and instructions for deploying on heroku are provided in the `/backend/README.md`

### Auth0 user tokens:
- Casting Assistant:
- Casting Director:
- Executive Producer:
