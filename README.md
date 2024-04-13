# TacoStore
The Taco Recipe Generator is a web application built using Express.js and EJS templates that allows users to randomly generate taco recipes based on their choice of protein: chicken, beef, or fish. The application features a simple and intuitive user interface where users can select their preferred protein option by clicking on the corresponding emoji button.

Upon selecting a protein option, the application fetches a random recipe from a predefined list of taco recipes stored in JSON format. Each recipe includes details such as the type of protein, salsa, and toppings, along with their respective ingredients and preparation methods.

Key Features:

Random Recipe Generation: Users can generate random taco recipes by selecting their preferred protein option.
Dynamic Rendering: The application dynamically renders the selected recipe on the webpage, providing users with a seamless browsing experience.
Responsive Design: The user interface is designed to be responsive and accessible across various devices and screen sizes.
Styling: The application is styled using CSS to enhance visual appeal and provide a cohesive user experience.
Technologies Used:

Express.js: A minimalist web framework for Node.js used to build the backend server and handle HTTP requests.
EJS Templates: Embedded JavaScript templates used to generate dynamic HTML content and render data on the client-side.
Body Parser: Middleware for Express.js used to parse incoming request bodies in a middleware before handlers.
CSS: Cascading Style Sheets used for styling the user interface and enhancing visual presentation.
JSON Data: Predefined taco recipes stored in JSON format to facilitate random recipe generation.
