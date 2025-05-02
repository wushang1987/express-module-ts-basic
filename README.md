# mcp-basic

This project is a basic implementation of an Express application using TypeScript. It demonstrates how to set up an Express server, define routes, and handle requests with controllers.

## Project Structure

```
mcp-basic
├── src
│   ├── app.ts                # Entry point of the application
│   ├── controllers
│   │   └── index.ts          # Contains the IndexController class
│   ├── routes
│   │   └── index.ts          # Sets up the application routes
│   └── types
│       └── index.ts          # Defines application-specific types
├── package.json               # Project metadata and dependencies
├── tsconfig.json              # TypeScript configuration
└── README.md                  # Project documentation
```

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (Node package manager)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd mcp-basic
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

### Running the Application

To start the application, run the following command:

```bash
npm start
```

### Usage

Once the application is running, you can access it at `http://localhost:3000`. You can test the routes defined in the application using a tool like Postman or curl.

### Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

### License

This project is licensed under the ISC License.