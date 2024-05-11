# React Redux Repositories List

This project is a simple React application that demonstrates the use of Redux for state management, along with TypeScript for type safety.

## Features

- Search for repositories on GitHub.
- Display loading state while fetching data.
- Display error message if search fails.
- Display list of repository names on successful search.

## Technologies Used

- React
- Redux
- TypeScript

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Make sure you have Node.js and npm installed.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Start the development server
   ```sh
   npm start
   ```

### Usage
   - Enter a search term in the input field and click the "Search" button.   
   - The app will fetch repositories from GitHub matching the search term.
   - The list of repository names will be displayed below the search form.

### Redux Pattern
The project follows a standard Redux pattern for state management:

   - Actions: Defined in src/state/action-creators.
   - Reducers: Defined in src/state/reducers.
   - Store: Configured in src/state/store.
   - Redux Hooks: Used in components for accessing and dispatching actions.
