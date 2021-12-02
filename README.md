# Install
Run ```yarn install``` or ```npm install`` to download all the libraries.
Edit your ```.env``` file and type your Sendbird application ID ```REACT_APP_SB_APP_ID=```
# SendBird Chat Client Overview
Chat client built as a learning project. Current state allows users to enter the app by entering a username. Users can select or create a channel from the /channels screen. Within the /chat screen, one to many users will be able to send/ receive messages, load previous messages, view active participants, leave the channel, and delete the channel if they are an admin/ creator of the channel.

There are three main screens within the app: 
- Login
- Channels
- Chat 

## Tech Used
- React
- [SendBird](https://www.sendbird.com)
- Material UI (and CSS-in-JS)
- dotenv (SendBird API key)
- React Router
- Redux/ React Redux

## Login
![alt text](https://github.com/warodri-sendbird/react-js-sendbird/blob/main/screenshot-login.png?raw=true)
## Channel list
![alt text](https://github.com/warodri-sendbird/react-js-sendbird/blob/main/screenshot-channels.png?raw=true)
## Chat view
![alt text](https://github.com/warodri-sendbird/react-js-sendbird/blob/main/screenshot-chat.png?raw=true)
