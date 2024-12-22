# Tracking-Charity-Donations
"A blockchain-based system to track charity donations, ensuring transparency and trust. Includes features for donors to monitor fund usage and an admin panel to update donation statuses with proof."


# Tracking Charity Donations Using Blockchain

## Description
This project leverages blockchain technology to create a transparent and secure system for managing charitable donations. It allows donors to track how their contributions are utilized and ensures funds are only released when specific conditions are met. The system is designed to build trust, reduce paperwork for charities, and improve fund management efficiency.

## Features
- **Donor Features**:
  - Create an account and log in.
  - Browse available campaigns.
  - Donate securely via a blockchain-based system.
  - Track transaction history and monitor how donations are used.
  - Receive notifications of successful transactions and thank-you messages.
- **Admin Features**:
  - Update campaigns with details and images of fund utilization.
  - Manage donation requests and validate charities.

## Functionalities
- Secure transactions using blockchain.
- Transparency in fund allocation.
- Real-time tracking of donation history.
- Pop-up notifications for transaction status.
- Detailed records accessible for accountability.

## Technology Stack
### Hardware Requirements
- **Processor**: Intel or AMD, 64-bit CPU.
- **RAM**: 4 GB or higher.
- **Storage**: 256 GB SSD.

### Software Requirements
- **Programming Languages**: Python, Blockchain, HTML.
- **Frameworks/Tools**: Django, Hardhat, React.
- **Operating System**: Windows 10 or above.
- **IDE**: Visual Studio Code.

## How to Run the Project
1. **Backend (Blockchain and Django)**:
   - Navigate to the `Tracking-charity-donation-using-blockchain-master` directory.
   - Install required dependencies: `npm install` (for Hardhat) and `pip install -r requirements.txt` (for Django).
   - Deploy the smart contract using `scripts/deploy.js`.
   - Start the Django server: `python manage.py runserver`.

2. **Frontend (React)**:
   - Navigate to the `frontend` folder.
   - Install dependencies: `npm install`.
   - Start the React app: `npm start`.

3. **Database**:
   - Ensure the database (`db.sqlite3`) is correctly set up and migrations are applied using `python manage.py migrate`.

4. **Blockchain Integration**:
   - Use the `Block.py` class to compute and verify blockchain hashes.

## Project Structure
- **`contracts/`**: Smart contracts for donation tracking.
- **`scripts/`**: Scripts for deploying and interacting with the blockchain.
- **`frontend/`**: React-based user interface.
- **`test/`**: Test cases for verifying smart contract functionality.
- **`manage.py`**: Django application entry point.
