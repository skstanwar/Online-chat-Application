#Real-Time Chat Application
This is a real-time chat application built using Node.js, Socket.io, and Express.js. It allows users to engage in instant messaging, create group chats, and communicate with other users in real-time.

##Installation
To run the application locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/skstanwar/Online-chat-Application.git
Navigate to the project directory:

bash
Copy code
cd Online-chat-Application
Install the dependencies:

Copy code
npm install
Usage
To start the application, use the following command:

sql
Copy code
npm start
This will start the server and the application will be accessible at http://localhost:3000.

Dependencies
The application relies on the following dependencies:

express: A fast and minimalist web framework for Node.js.
socket.io: A library for real-time bidirectional event-based communication.
moment: A library for formatting dates and timestamps.
dotenv: A module for loading environment variables from a .env file.
These dependencies are automatically installed when running npm install.

Project Structure
The project structure is organized as follows:

index.js: The entry point of the application.
public/: Contains the client-side code (HTML, CSS, JavaScript) for the chat application.
routes/: Contains the server-side code for handling routes.
utils/: Contains utility functions for the application.
views/: Contains the HTML templates for rendering the chat application.
Contributing
Contributions to the project are welcome. If you encounter any bugs or have suggestions for improvement, please open an issue on the GitHub repository.

License
This project is licensed under the MIT License.