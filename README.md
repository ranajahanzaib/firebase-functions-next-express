# Express/Next.js for Firebase Cloud Functions

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

Use this template to instantly create Express/Next.js project and deploy on [Firebase Cloud Functions](https://firebase.google.com/products/functions).

## Getting Started

Follow the steps below to create and deploy new REST API on Firebase.

### **1** - Create New Firebase Project

Go to [Firebase Console](https://console.firebase.google.com) and create a new project, if you haven't already.

### **2**: Add ProjectID

Add your project ID to the `.firebaserc` file.

File: `.firebaserc`

```json
{
  "projects": {
    "default": "FIREBASE_PROJECT_ID"
  }
}
```

Replace `FIREBASE_PROJECT_ID` with your Firebase Project ID

### **3**: Install Dependencies

Install the required dependecies described in `package.json` using the commands below.

```sh
npm install -g firebase-tools # required for Firebase CLI
firebase login # Login to Firebase CLI, required once
npm install
```

### **4**: Deploy on Firebase Cloud Functions

Run the following commands to deploy your project on Firebase Cloud Functions.

```sh
npm run deploy
```

The above commmand will automatically create an optimized build for your project, and deploy it on Firebase Cloud Functions.

## Contributing

We'd love to accept your patches and contributions to this project. There are just a few guidelines you need to follow.

### Code of Conduct

This project follows [Contributor Covenant](https://www.contributor-covenant.org/)
as it's Code of Conduct, and we expect all project participants to adhere to it.
Please read the [full guide](./CODE_OF_CONDUCT.md) so that you can understand
what actions will not be tolerated.

### Contributing Guide

Read our [contributing guide](./CONTRIBUTING.md) to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to project.

### LICENSE

This project is licensed under the [MIT License](./LICENSE), meaning that you're free to modify, distribute, and / or use it for any commercial or private project.
