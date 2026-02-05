# Disability Rights Texas - Amazon Q Business Integration

A web application that integrates Amazon Q Business to provide AI-powered assistance for disability rights information and resources.

## Project Overview

This project creates an accessible chatbot interface powered by Amazon Q Business that helps users find information about disability rights, services, and resources provided by Disability Rights Texas. The application includes:

- AI-powered chat interface using Amazon Q Business
- Document and website knowledge base integration
- Feedback mechanism for responses
- Accessibility features

## Disclaimers

Customers are responsible for making their own independent assessment of the information in this document.

This document:

(a) is for informational purposes only,

(b) represents current AWS product offerings and practices, which are subject to change without notice, and

(c) does not create any commitments or assurances from AWS and its affiliates, suppliers or licensors. AWS products or services are provided "as is" without warranties, representations, or conditions of any kind, whether express or implied. The responsibilities and liabilities of AWS to its customers are controlled by AWS agreements, and this document is not part of, nor does it modify, any agreement between AWS and its customers.

(d) is not to be considered a recommendation or viewpoint of AWS

Additionally, all prototype code and associated assets should be considered:

(a) as-is and without warranties

(b) not suitable for production environments

(d) to include shortcuts in order to support rapid prototyping such as, but not limited to, relaxed authentication and authorization and a lack of strict adherence to security best practices

All work produced is open source. More information can be found in the GitHub repo.

## Repository Structure

```
/
├── frontend/               # React frontend application
│   ├── public/             # Public assets
│   ├── src/                # Source code
│   │   ├── Assets/         # Images and SVG files
│   │   ├── Components/     # React components
│   │   ├── services/       # API services
│   │   └── utilities/      # Helper functions and contexts
│   ├── .env                # Environment variables
│   └── package.json        # Dependencies
├── DEPLOYMENT.md           # Deployment instructions
└── template.json           # CloudFormation template for backend
```

## Features

- **AI-Powered Chat**: Utilizes Amazon Q Business to answer questions about disability rights
- **Document Knowledge Base**: Integrates with S3-stored documents and website content
- **Feedback System**: Allows users to rate responses for continuous improvement
- **Accessibility**: Built with accessibility in mind for users with disabilities

## Technology Stack

- **Frontend**: React.js
- **Backend**: AWS Lambda, API Gateway
- **AI Service**: Amazon Q Business
- **Data Sources**: S3 documents, Web crawler
- **Deployment**: AWS CloudFormation, AWS Amplify

## Getting Started

1. See [DEPLOYMENT.md](DEPLOYMENT.md) for detailed setup instructions
2. Configure Amazon Q Business as described in the deployment guide
3. Deploy the backend using CloudFormation
4. Set up and deploy the frontend using AWS Amplify

## Development

To run the application locally:

```bash
cd frontend
npm install
# Create .env file with required environment variables
npm start
```
