# Worldwise

**Note: This project is based on [The Ultimate React Course by Jonas Schmedtmann](https://www.udemy.com/course/the-ultimate-react-course/)**.

Basic web application designed for tourists to log the cities they've visited and leave personal notes on favorite destinations. Developed to showcase the functionality of React Router, the Context API, and integration with the Leaflet library for interactive map functionality.

**Live Deployment: [https://pjf3av-worldwise.netlify.app/](https://pjf3av-worldwise.netlify.app/)**.

## Please note!

The map interactivity, including loading city details, saving new cities, and deleting cities from the list are not available functionalities on the live Netlify deployment linked above. To demo full functionalities of the app, please see the instructions below for how to clone, start the local JSON server, and deploy the app.

## JSON Server

The main branch of this repo relies on a live JSON server, a simulation of interaction with a backend server to provide question data. The live version (on the "netlify" branch) loads the questions directly from the JSON file in the "src" folder. 

## Key Features
- User authentication
- Mock API for loading/saving destinations
- Interactive map for viewing saved destinations and adding new ones
- Shell of full site

## Development Technologies
- React
- Context API
- React Router
- React Leaflet & Leaflet (map)
- React Datepicker
- CSS Modules (styling)

## Getting Started
To clone and deploy this project locally, follow these simple steps.

### Prerequisites

First, make sure you have the latest version of npm:

```bash
npm install npm@latest -g
```

### Installation

1. Clone this repo

```
git clone https://github.com/pjf3av/worldwise.git
```

2. Install NPM packages

```
npm i
```

3. Start JSON server

```
npm run server
```

4. Start server

```
npm run dev
```
