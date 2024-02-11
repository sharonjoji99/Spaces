# Spaces
Introducing Spaces, the ultimate community-driven exploration app! Imagine a platform where you can curate and share your favorite spots, transforming your personal journeys into shared treasures. Spaces is all about connecting through the places you love, bringing communities together, and rediscovering the joy of exploration. Unlike conventional social media, we've ditched follower counts and popularity contests to create an honest space dedicated to community-driven discovery and authentic connections. Think of it as your own social map, where you can pin all your cherished places and relive the memories.


# What it does
The platform is built around the smallest unit called 'spaces.' Each space is an individual's experience that can be discovered by any other individual. Spaces with similar properties can be grouped into 'Collections' for easy organization and sharing purposes. We utilize tags to uncover and establish communities, with the tags serving as a means to amplify the voices of these communities on our platform.
[![Alt text](https://img.youtube.com/vi/LUpNAgsWKno/0.jpg)](https://www.youtube.com/watch?v=LUpNAgsWKno)


# How we built it
We began by brainstorming and finalizing our concept, with a strong commitment to promoting inclusion and supporting the community. Next, we created wireframes and sought guidance from mentors. We concentrated on prioritizing the features that set our platform apart as unique. We promptly started developing the frontend and subsequently worked on the database design. Once the database design was finalized, we implemented the API logic and resolved any remaining bugs. Additionally, we conducted UI touch-ups to ensure a polished user experience.
![wireframe](https://github.com/amritav/Spaces-hackNC/assets/19224584/eec43849-82a5-4c30-97a0-aca3e56e6d1d)


  
We aimed to make our app more than just another run-of-the-mill social media or reviews platform. This goal posed significant challenges, but we're proud to have created a unique and meaningful experience for our users.



## Install and Run the Project
Clone the project into your system.
```sh
$ git clone https://github.com/deepr41/Spaces.git
$ cd Spaces
```

Install the dependencies for frontend.
```sh
$ cd frontend
$ npm install
```

Install the dependencies for backend.
```sh
$ cd backend
$ npm install
```
The application uses mongodb on it's deafult port for the database. If you don't have it already installed, you can use mongodb using docker using the below command.
```sh
$ docker run -p 27017:27017 -d mongo:latest
```
Now you are ready to start the application.
Start the backend and frontend separetly in different terminals

For backend
```sh
$ cd backend
$ npm start
```

For frontend
```sh
$ cd frontend
$ npm run dev
```

Open the application at `http://localhost:5173`

## More info
This project was part of my team's submission to hack_nc hackathon hosted at NCSU. We were awarded the best project prize. Find more details at [Devpost project link - Spaces](https://devpost.com/software/spaces-405m26).


# What's next for Spaces
This marks just the beginning for Spaces. With a solid foundation and a clear vision of our goals, we are confident that our application will continue to soar to greater heights. In the near future, we have exciting features on the horizon, such as the ability to share your favorite communities and collections with friends. Main feature we would like to bring into the app is the multi-city and multi-country communities. Also stay tuned for the upcoming 'Near' tab, which will display the most exciting places within a 5-mile radius, making it easier for you to explore the nearby gems. We'll also introduce short video uploads and a rich markdown editor for creating engaging content blocks.
