# Node.js Assignments

## Completed Time
Approximately 4 hours

## Technology
- **API:** Express.js, MongoDB

## Project Overview

### Backend Project Architecture
The project follows a Service-Controller-Model architecture.

### How to Run

#### Option 1: Using Docker

1. **Clone the project:**
   ```
   git clone https://github.com/zulkar29/node-js-assingment.git
   ```

2. **Build Docker image:**
   ```
   docker build -t my-node-app .
   ```

3. **Run Docker container:**
   ```
   docker run -p 3001:3001 my-node-app
   ```

#### Option 2: Without Docker

1. **Clone the project:**
   ```
   git clone https://github.com/zulkar11/Service-controller-pattern.git
   ```

2. **Navigate to the project directory:**
   ```
   cd Service-controller-pattern
   ```

3. **Install dependencies:**
   ```
   npm install
   ```

4. **Run the project:**
   ```
   npm run dev
   ```

### URLs
- **Base URL:** [http://localhost:3001/](http://localhost:3001/)

### API Documentation
API documentation is available on [Postman documentation](https://documenter.getpostman.com/view/14084783/2s9Yyy9JnU)


### Containerization
- Docker-based containerization for easy deployment.

### API Response Enhancement
- API responses include validation messages.

### API Endpoint Naming Convention
- Followed a consistent API endpoint naming convention.
