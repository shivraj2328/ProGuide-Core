# Day 1 - Product Planning

## Completed 
- Finalize project idea
- Defined user roles
- Defined core features
- Created documentation structure

## Learned
- Importance of product planning before development
- Difference between MVP and full product

## Next Plan
- Setup Frontend and Backend
- Configure PostgreSQL
- Initialize GitHub Repository


# Day 2 - Environment Setup

## Completed
- Created ProGuide-Core directory
- Created frontend folder and did frontend setup
- Installed Tailwind + Vite setup
- Created backend structure src/(controllers, routes, models, middleware, config, utils)
server.js
- Installation and setup of postgresql-18.4-1

## Learned 
- Frontend Setup:
    Steps:
    i. Create React app by triggering - npm create      vite@latest .
    ii. Choosing Framework as React
    iii. Choosing Variant as JavaScript.
    iv. Installed Dependencies
    v. Start Development server by hitting npm run dev.

    1. Hitting npm create vite@latest . :
        npm - Node Package Manager - It is the Product's Delivery Service. It is the world's largest registry of free software code. We can think of it as a Play Store specifically for developers. Instead of writing complex features from scratch, we use npm to download tools created by other programmers.
    2. Vite :
        Browser cannot read special React code (.jsx) directly. Vite instantly translates it into standard HTML, CSS and JavaScript.
    3. Localhost :
        Standard hostname that means "This Computer". It represents a private web network that exists only inside your own physical machine.


- Tailwind Setup:
    Setup Tailwind by hitting - npm install tailwindcss @tailwindcss/vite


- Backend Setup:
    Steps:
    i. Initialize the Node.js Project by hitting "npm
        init -y". This generated a default configuration file named package.json.
    ii. Installing Core Production Dependencies by
        hitting "npm install express cors dotenv pg bcrpyt jsonwebtoken" this downloaded six major libraries. 
    iv. Installing development dependencies:
        Hitting "npm install --save-dev nodemon" that install nodemon specifically as a development tool.
    v. Constructing the clean Architecture Folder
        Structure. By hitting "mkdir controller, routes, models, middleware, config, utils" I designed a robust, MVC-inspired file structure inside the "src" directory.
    vi. Created server.js and update the 
    

    Packages: 
    1. express: 
        A minimalist web framework to handle HTTP requests (GET,POST) and routing.
    2. cors: 
        Middleware ensuring your frontend(e.g. React on port 3000) is allowed to securely talk your backend (port 5000).
    3. dotenv: 
        A utility that securely loads environment variables (like database passwords) from hidden .env file to Node's process.env.
    4. pg: 
        A non-blocking PostgreSQL client that allows the Node.js to communicate and run SQL queries against a Postgres database.
    5. bcrypt:
        A hashing algorithm used to securely salt and encrypt user passwords before storing them.
    6. jsonwebtokens(JWT):
        A standard used to issue digital tokens to users upon login, allowing them to remain securly authenticated.
    7. nodemon:
        It wraps your Node process and keeps an active file watcher on your directory. Whenever a .js or .json file is modified, it kills the old server instance and instantly spins up a fresh one so you don't have to manually restart it.
    8. config :
        Contains database credentials and environment configuration scripts.
    9. controller:
        Holds the actual business logic and response rules for API paths.
    10. models:
        Declares the database schemas or table layout(PostgreSQL definitions)
    11. middleware:
        Stores gatekeeping code, like checking if a user's JWT token is valid before letting them view data.
    12. routes:
        Maps endpoints (like /api/users) to their respective controllers.
    13. utils: 
        Houses reusable helper functions (like date formatters or validation math).


        