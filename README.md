# Express API Starter

A minimal, production-ready starter template for building highly scalable Node.js and Express microservices. 

This boilerplate is designed to save setup time while enforcing best practices for routing, global error handling, and architecture structure.

##  Features

- **Express.js** setup with minimal overhead.
- **Global Error Handling** middleware to catch unhandled exceptions and format API responses cleanly.
- **Microservice Ready** architecture for easy scaling and deployment.
- **No Clutter** - zero unnecessary dependencies.

##  Quick Start

### 1. Clone the repository
\`\`\`bash
git clone https://github.com/vincentKiee/express-api-starter.git
cd express-api-starter
\`\`\`

### 2. Install dependencies
*(Currently uses native Node.js modules, so no install is needed until you add a database ORM or validation library).*

### 3. Run the server
\`\`\`bash
node index.js
\`\`\`
The server will start locally at `http://localhost:3000`.

##  Project Structure

\`\`\`text
express-api-starter/
│
├── middleware/
│   └── errorHandler.js    # Global API error catcher
├── index.js               # Entry point and server configuration
├── package.json           # Project metadata
└── README.md
\`\`\`

##  Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
