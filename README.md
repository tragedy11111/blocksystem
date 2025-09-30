
# Blockchain System with DID and Smart Contracts

This project is a blockchain-based system integrating Decentralized Identifiers (DID), Smart Contracts, a Vue.js frontend, and a Spring Boot backend.

## Features

* **Smart Contracts**: Deployed on a blockchain to handle the core business logic and data integrity.
* **DID (Decentralized Identifiers)**: Used to securely manage identities in a decentralized way.
* **Frontend (Vue.js)**: A modern and responsive user interface built with Vue.js for interaction with the system.
* **Backend (Spring Boot)**: A robust backend service developed with Spring Boot, managing user requests, business logic, and interactions with the blockchain.

## Getting Started

### Prerequisites

* Node.js (for frontend)
* Java 8+ (for backend)
* Spring Boot (for backend)
* Blockchain network (e.g., Ethereum) running your smart contracts

### Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/tragedy11111/blocksystem.git
   ```

2. **Frontend (Vue.js):**

   Navigate to the frontend directory and install dependencies:

   ```bash
   cd frontend
   npm install
   npm run serve
   ```

3. **Backend (Spring Boot):**

   Navigate to the backend directory and run the Spring Boot application:

   ```bash
   cd backend
   ./mvnw spring-boot:run
   ```

4. **Deploy Smart Contracts**:

   Deploy your smart contracts to a blockchain (e.g., Ethereum) and ensure the contract addresses are correctly configured in the backend.

### Usage

* Access the application via the frontend running at `http://localhost:8080`.
* Interact with the blockchain and DID-based identity features.

## Contributing

Feel free to fork the repository and submit pull requests. Please make sure your code follows the project's coding standards and includes tests.

## License

This project is licensed under the MIT License.


