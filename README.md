# **Currency Converter**

### **Table of Contents**
- Project Overview
- Features
- Technologies Used
- Project Structure
- Setup and Installation
- Running the Project
- Deployment
- Contributing
- License
- Author

---

### **Project Overview**
This project is a Currency Converter web application that converts one currency to another based on real-time exchange rates. It is a Java-based web application built using JSP (JavaServer Pages) and related technologies. The repository is configured to integrate Continuous Integration pipelines and deployment support.

---

### **Features**
- **Real-Time Conversion**: Converts currency values based on the latest rates.
- **Web-Based Interface**: Simple and user-friendly interface designed with HTML and CSS.
- **Modular Design**: Separation of concerns using JSP and XML configurations.
- **CI/CD Integration**: Supports Jenkins and Azure Pipelines for continuous integration and deployment.
- **Cross-Browser Support**: Works across major browsers.
- **Scalable**: Configured with Maven for dependency and build management.

---

### **Technologies Used**
The project uses the following technologies and tools:

- **Java (JSP & Servlets)** – Backend logic.
- **HTML/CSS** – Frontend design.
- **Apache Maven** – Project build and dependency management.
- **Azure Pipelines** – CI/CD support.
- **Jenkins** – Automation server for builds and testing.
- **XML (web.xml, pom.xml)** – Configuration management.
- **Version Control**: Git and GitHub.

---

### **Project Structure**
The following files and folders are part of the repository:

```plaintext
Currency-Converter/
│
├── .gitignore           # Specifies files ignored in Git version control
├── Jenkinsfile          # Jenkins CI/CD pipeline configuration
├── LICENSE              # License details for the project
├── MANIFEST.MF          # Manifest file for Java applications
├── azure-pipelines.yml  # Azure Pipelines CI/CD configuration
├── index.jsp            # Main JSP file for user interface
├── pom.xml              # Maven configuration and project dependencies
├── style.css            # CSS file for project styling
└── web.xml              # Configuration for the Java web application
index.jsp: Serves as the main page with the user interface for currency conversion.
pom.xml: Handles all Maven dependencies and project build lifecycle.
web.xml: Configures servlets, context parameters, and deployment settings.
azure-pipelines.yml: Defines the CI/CD workflow for Azure Pipelines.
Jenkinsfile: Pipeline script for Jenkins CI/CD integration.
style.css: Custom styling for the application’s user interface.
```
---

### **Setup and Installation**
Follow these steps to set up and run the project locally:

1. **Prerequisites**
- Java Development Kit (JDK 8+)
- Apache Maven (Ensure mvn is available in your environment)
- Apache Tomcat Server (or any Java Servlet container)
- Git

2. Steps to Run the Project
- Clone the Repository

```bash
git clone https://github.com/stephenombuya/Currency-Converter.git
cd Currency-Converter
```

3. Build the Project using Maven

```bash
mvn clean install
```

4. Deploy to Tomcat

- Place the generated .war file into your Tomcat webapps directory.
- Start the Tomcat server.

5. Access the Application Open your browser and go to:

```bash
http://localhost:8080/Currency-Converter/index.jsp
```

6. Running the Project
- The application will provide a user-friendly form where you can:

  - Enter the currency you want to convert.
  - Select the target currency.
  - View the converted value in real-time.

7. Deployment
The repository supports CI/CD pipelines:

  - **Jenkins**:
    - The Jenkinsfile automates builds and testing.
  - **Azure Pipelines**:
    - The azure-pipelines.yml script ensures deployment workflows in Azure.

  - To configure:

    - Set up Jenkins or Azure Pipelines in your environment.
    - Provide the necessary credentials and environment variables.

---

### **Contributing**
Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature/YourFeatureName
```

3. Make changes and test.
4. Commit changes.

```bash
git commit -m "Add feature: YourFeatureName"
```
5. Push to your fork.

```bash
git push origin feature/YourFeatureName
```

6. Submit a pull request.

---

### **License**
This project is licensed under the GNU General Public License v3.0. See the `LICENSE` file for details.

---

### **Author**
Stephen Ombuya

For questions, feedback, or suggestions, contact:

GitHub: [stephenombuya](https://github.com/stephenombuya)
