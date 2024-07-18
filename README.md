# WYSIWYG Web Page Builder

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Technologies Used](#technologies-used)
6. [Implementation Details](#implementation-details)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

This project is a WYSIWYG (What You See Is What You Get) web page builder inspired by platforms like WordPress and Wix. It allows users to design web pages through an intuitive, drag-and-drop interface without writing code. The builder is built using the MERN stack (MongoDB, Express.js, React, Node.js) and incorporates various advanced features to enhance user experience.

## Features

1. **Rich Text Formatting**: Apply various text formatting options such as bold, italic, underline, and lists.
2. **Resizing and Cropping Images**: Resize and crop images to fit the design.
3. **Customizable Button Component**: Create buttons with customizable text, color, and actions.
4. **Responsive Design Preview**: Preview the design on desktop, tablet, and mobile views.
5. **Saving and Loading**: Save page designs to MongoDB and load them later.
6. **Export/Import Function**: Export designs as JSON and import them back into the editor.
7. **SEO Optimization Tools**: Manage SEO tags and attributes.
8. **User Authentication**: Secure workspaces and designs with login/logout functionality.
9. **Draggable Components**: Intuitively drag and drop components to design pages.
10. **Generate HTML**: Obtain HTML code for the arranged components with specified settings.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wysiwyg-web-page-builder.git
   cd wysiwyg-web-page-builder
   ```

2. Install server dependencies:
   ```bash
   cd server
   npm install
   ```

3. Install client dependencies:
   ```bash
   cd ../client
   npm install
   ```

4. Start the server:
   ```bash
   cd ../server
   npm start
   ```

5. Start the client:
   ```bash
   cd ../client
   npm start
   ```

## Usage

1. Register and log in to your account.
2. Start designing your web page using the drag-and-drop interface.
3. Use the rich text editor to format text.
4. Resize and crop images as needed.
5. Customize buttons and other components.
6. Preview your design on different devices.
7. Save your design to MongoDB or export it as JSON.
8. Import JSON files to restore designs.
9. Use the SEO tools to optimize your page.
10. Generate HTML code for your design.

## Technologies Used

- **Frontend**: React, Draft.js/Quill.js, Cropper.js, HTML5 Canvas API, Tailwind CSS, Redux, localStorage.
- **Backend**: Node.js, Express.js, MongoDB, Mongoose.
- **Authentication**: bcrypt, JWT (JSON Web Tokens).
- **State Management**: Redux.
- **Deployment**: Vercel for Frontend, render for backend

## Implementation Details

### Rich Text Formatting
- **Technology**: Draft.js/Quill.js
- **Details**: Integrated a rich text editor for dynamic text formatting.

### Resizing and Cropping Images
- **Technology**: HTML5 Canvas API, Cropper.js
- **Details**: Developed an image holder component with resizing and cropping functionalities.

### Customizable Button Component
- **Technology**: React
- **Details**: Implemented a button component with customizable text, color, and actions.

### Responsive Design Preview
- **Technology**: React
- **Details**: Added buttons to switch between desktop, tablet, and mobile views.

### Saving and Loading
- **Technology**: MongoDB, Mongoose
- **Details**: Enabled saving designs to MongoDB and loading them back.

### Export/Import Function
- **Technology**: JSON
- **Details**: Allowed exporting and importing designs as JSON.

### SEO Optimization Tools
- **Technology**: React
- **Details**: Provided settings to manage SEO tags and attributes.

### User Authentication
- **Technology**: bcrypt, JWT
- **Details**: Implemented login/logout functionality with secure password hashing and token-based authentication.

### Draggable Components
- **Technology**: React, React DnD
- **Details**: Enabled intuitive drag-and-drop for designing pages.

### Generate HTML
- **Technology**: React, HTML
- **Details**: Added a feature to generate HTML code for the designed components.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes.
4. Commit your changes: `git commit -m 'Add some feature'`.
5. Push to the branch: `git push origin feature-name`.
6. Open a pull request.

## License

This project is developed by Yernagula Siddartha . 
