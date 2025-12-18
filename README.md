# Node.js Server-Sent Events Demo


## Features
- Minimal Express server with SSE endpoint (`/events`)
- using `EventSource`
- Streams messages every two second
- Auto-updates the browser without refresh

## Installation
```bash
# Clone the repository
git clone https://github.com/shreyas135/nodejs-see-demo.git

# Navigate into the project
cd nodejs-see-demo

# Install dependencies
npm install

## Run
node index.js

## Check on Browser
http://localhost:3000/events
