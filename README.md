
---

# T-Shirt Enterprise Automation with UiPath Studio

This repository contains the UiPath Studio project designed to automate the documentation processes for a t-shirt manufacturing enterprise. The automation focuses on three main areas:

1. **Buying Raw Materials**: Scraping data from online stores and storing it in an Excel file.
2. **Design Confirmation**: Sending the fabric design details to the design department via email.
3. **Transportation**: Scraping data from courier services for transportation planning.

## Project Overview

### 1. Buying Raw Materials

- **Description**: This part of the automation scrapes data from online stores like IndiaMart to gather information about available raw materials, specifically different types of fabrics.
- **Output**: The scraped data is stored in an Excel file, categorized based on fabric type, price, supplier details, etc.
- **Purpose**: Streamlines the raw material procurement process by automating data collection, reducing manual effort and errors.

### 2. Design Confirmation

- **Description**: Once the raw material (fabric) has been selected and approved, this automation sends an email to the design department with all the necessary details about the fabric, such as dimensions, GSM (Grams per Square Meter), and other relevant specifications.
- **Output**: An automated email is sent to the design department with an attached document containing the fabric details.
- **Purpose**: Ensures that the design department receives accurate and timely information about the materials for the upcoming designs.

### 3. Transportation

- **Description**: This part of the automation scrapes data from various courier services to find the best options for transporting the raw materials and finished products.
- **Output**: The scraped data is compiled into an Excel file, listing the available courier services, prices, delivery times, and other relevant details.
- **Purpose**: Optimizes the transportation process by comparing courier options and selecting the most efficient and cost-effective service.

## Requirements

- **UiPath Studio**: The project was developed using UiPath Studio, so you'll need to have it installed to run the automation.
- **Excel**: The automation outputs data in Excel format, so make sure you have Excel installed on your system.
- **Email Configuration**: Ensure that the email settings are configured in UiPath Studio to send emails as part of the design confirmation process.

## Installation

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/tshirt-enterprise-automation.git
   ```
2. Open the project in UiPath Studio.
3. Update the selectors and paths as needed to match your environment and data sources.
4. Configure the email activity with your email credentials.
5. Run the automation sequence.

## Usage

- **Running the Automation**: Simply open UiPath Studio, select the main sequence (e.g., `Main.xaml`), and click "Run" to start the automation.
- **Customizing the Workflow**: You can modify the workflow by opening the relevant `.xaml` files in UiPath Studio and making changes to the activities, selectors, and variables.

## Contributing

If you find any issues or have suggestions for improvement, feel free to create an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README further to suit your specific project details.
