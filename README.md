# DineLine - Restaurant Queuing System

DineLine is a modern and efficient restaurant queuing system that simplifies the dining experience for both customers and restaurant staff. With DineLine, you can manage your restaurant's waiting list, estimate wait times, and provide customers with real-time updates on their table availability.

## Features

- **Admin Dashboard**: Restaurant staff can create and manage queues, removing parties from the list when tables are ready.

- **Customer Queue Management**: Customers can add themselves to the queue, specifying the size of their party.

- **Real-Time Updates**: Receive instant notifications when it's your turn to be seated.

- **Estimated Wait Times**: DineLine leverages machine learning to estimate wait times accurately.

- **User Authentication**: Secure login for both admins and customers.

## Technologies Used

- **Frontend**: React, TypeScript, Next.js
- **Backend**: Node.js, Express
- **Database**: MySQL hosted on Azure
- **Machine Learning**: Python with Flask (Azure Machine Learning Service)
- **Real-Time Updates**: WebSocket (Socket.io)
- **Authentication**: Auth0 (or Firebase)
- **Deployment**: Azure Web App Service

## Getting Started

### Prerequisites

- Node.js and npm installed
- MySQL database instance (hosted on Azure or any other platform)
- Azure Machine Learning Service account (for the machine learning model)
- Auth0 or Firebase account (for authentication)

### Installation

1. Clone the repository:
```git clone https://github.com/peterspr/dine-line.git```
2. Navigate to the client and server directories and install dependencies:
```cd client
npm install

cd ../server
npm install```
3. Configure the environment variables, including database connection details, authentication credentials, and machine learning model endpoints.
4. Start the frontend and backend servers:
```# Frontend
cd client
npm run dev

# Backend
cd server
npm start```
##Documentation

For detailed setup instructions, API documentation, and user guides, please refer to the documentation directory.
##Contributing

We welcome contributions from the open-source community. Please see our [Contribution Guidelines](https://github.com/peterspr/dine-line/CONTRIBUTE.md) for more information on how to get involved.

##License

This project is licensed under the [MIT License](https://github.com/peterspr/dine-line/LISENCE.md).