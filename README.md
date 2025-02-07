# SOW Tracker ![version](https://img.shields.io/badge/version-1.0.0-blue) ![UNLICENSED](https://img.shields.io/badge/license-UNLICENSED-orange)

Powered By 
![SAPUI5](https://img.shields.io/badge/SAPUI5-green) ![Nodejs](https://img.shields.io/badge/NodeJS-orange) ![NextJS](https://img.shields.io/badge/NestJS-red)

## Overview

SOW Tracker is an SAP Fiori application developed using the Fiori freestyle template. It helps manage Statements of Work (`SOW`) efficiently within an organization.

## Application Details

| Attribute                        | Value                             |
| -------------------------------- | --------------------------------- |
| **Generation Date**              | Mon Feb 19 2024 11:49:53 GMT+0530 |
| **App Generator**                | `@sap/generator-fiori-freestyle`    |
| **App Generator Version**        | ![1.12.2](https://img.shields.io/badge/1.12.2-blue)                            |
| **Platform**                     | ![Visual_Studio Code](https://img.shields.io/badge/Visual_Studio_Code-purple)                |
| **Template Used**                | ![simple](https://img.shields.io/badge/simple-gold)                            |
| **Service Type**                 | ![None](https://img.shields.io/badge/None-red)                              |
| **Service URL**                  | ![N/A](https://img.shields.io/badge/N/A-red)                               |
| **Module Name**                  | ![sow_tracker](https://img.shields.io/badge/sow__tracker-yellow)                       |
| **Application Title**            | ![SOW Tracker](https://img.shields.io/badge/SOW_Tracker-orange)                       |
| **Namespace**                    | ![com.candentech](https://img.shields.io/badge/com.candentech-blue)                    |
| **UI5 Theme**                    | ![sap_horizon](https://img.shields.io/badge/sap_horizon-green)                       |
| **UI5 Version**                  | ![1.120.7](https://img.shields.io/badge/1.120.7-blue)                           |
| **Enable Code Assist Libraries** | ![False](https://img.shields.io/badge/False-red)                             |
| **Enable TypeScript**            | ![False](https://img.shields.io/badge/False-red)                             |
| **Add ESLint Configuration**     | ![False](https://img.shields.io/badge/False-red)
|

## Prerequisites

Ensure that you have the following installed:

- Node.js LTS version (https://nodejs.org)
- npm (bundled with Node.js LTS version)

## Installation

1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project folder:
   ```sh
   cd sow_tracker
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Running the Application

To start the application, run the following command from the project root:

```sh
npm start
```

## Project Structure

```
├── webapp
|   ├── Assets                   # Images needed for application 
│   ├── controller               # Controllers for views
|   ├── css                      # Styles
|   ├── enum                     # Constants/Enums for the application
│   ├── view                     # XML views for the UI
│       └── fragments            # XML fragments for the UI
│   ├── model                    # Data models
│   ├── Component.js             # Application bootstrap
│   ├── index.html               # Entry point of the app
├── package.json                 # Project dependencies and scripts
└── ui5.yaml                     # UI5 configuration
```

## Deployment

For deployment, configure and use an SAP Fiori launchpad or SAP Business Technology Platform (BTP).

## License

This project is licensed under ![UNLICENSED](https://img.shields.io/badge/UNLICENSED-orange)
