# ✈️ SmartVacay

Final project for Batch 1190 Web Development course.<br><br>
This Web App allows user to create an itinerary for their trip with a single click of a button.<br>
After creating a trip with the destination and dates, a user will save all the location they want to go on their vacation, and the app will create the itinerary for you based on how far the locations are from each other to minimize travel time for your holiday.<br>

<div class="row">
<img src="https://tyhyun.me/images/projects/smart1.png" width="15%">
<img src="https://tyhyun.me/images/projects/smart2.png" width="15%">
<img src="https://tyhyun.me/images/projects/smart3.png" width="15%">
<img src="https://tyhyun.me/images/projects/smart4.png" width="15%">
<img src="https://tyhyun.me/images/projects/smart5.png" width="15%">
</div>
<br>
App home: https://www.smartvacay.app

## Team Members

Donald Chow [Github](https://github.com/Donald-Chow/), [Linkedin](https://www.linkedin.com/in/donald-wh-chow/)<br>
Yin Lee [Github](https://github.com/tyhyun309)<br>
Joyce Lau Homing [Github](https://github.com/jshizuki), [Linkedin](https://www.linkedin.com/in/joyce-lau-046b8689)<br>
Arthur Andrade West [Github](https://github.com/Arthur-Andrade194), [Linkedin](https://www.linkedin.com/in/arthur-andrade-west/)<br>

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables.
```
# Google
GOOGLE_API_SERVER_KEY=##################
GOOGLE_API_BROWSER_KEY=##################

# Email
OUTLOOK_ADDRESS=########@########.com
OUTLOOK_APP_PASSWORD=##################

```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping
