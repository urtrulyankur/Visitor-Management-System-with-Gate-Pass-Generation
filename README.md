

# Visitor Management System with Gate Pass Generation

## Project Overview

The Visitor Management System with Gate Pass Generation is a web-based application designed to simplify and secure the process of registering and managing visitors in an organization. The system allows visitors to input their details, capture a photo, and generate a personalized gate pass, which can then be printed for entry. This project is ideal for organizations looking to enhance their security measures and streamline visitor management.

## Features

- **Visitor Registration:** 
  - A user-friendly form for visitors to enter their details such as name, contact number, company, purpose of visit, and more.
  - Data is securely stored in the browser's local storage for easy retrieval during the session.

- **Photo Capture:** 
  - Integration with the device’s camera allows visitors to capture their photos directly through the web interface.
  - The captured photo is displayed and stored in the local storage for inclusion in the gate pass.

- **Gate Pass Generation:** 
  - Automatically generates a gate pass with the visitor’s details and photo upon form submission.
  - The gate pass is designed to be print-ready, with all necessary visitor information clearly displayed.

- **Print Functionality:**
  - A dedicated print button allows for easy printing of the generated gate pass, with unnecessary elements hidden in the print view.

- **Responsive Design:**
  - The application is designed to work seamlessly across different devices, ensuring a consistent user experience.

## Technologies Used

- **HTML5/CSS3:** For the structure and styling of the web pages.
- **JavaScript:** For handling form submission, photo capture, and local storage management.
- **Web APIs:** Used to access the device’s camera and handle media streams.

## Installation

To get started with this project, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/visitor-management-system.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd visitor-management-system
   ```

3. **Open the project:**

   You can open the `index.html` file in your preferred web browser to start using the application.

## Usage

1. Open the application in a web browser.
2. Click on "Take Photo" to start the camera and capture the visitor's photo.
3. Fill out the visitor registration form with all the required details.
4. Submit the form to generate the gate pass.
5. Click the "Print Gate Pass" button to print the generated gate pass.

## Project Structure

```
visitor-management-system/
│
├── index.html           # Main form page for visitor registration
├── display.html         # Page for displaying and printing the gate pass
├── styles.css           # CSS file for styling the pages
├── display.css          # CSS file specifically for the gate pass display page
├── script.js            # JavaScript file for handling camera and form submission
└── display.js           # JavaScript file for loading gate pass data and handling print
```

## Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are welcome.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any inquiries, feel free to reach out via email: ankur78912@gmail.com
