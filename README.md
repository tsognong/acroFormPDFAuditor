# AcroForm PDF Auditor

A lightweight, web-based tool for inspecting, organizing, and validating AcroForm PDF fields with custom naming conventions—no database required, completely free to use.

## Overview

AcroForm PDF Auditor is a standalone application designed to streamline the management and validation of AcroForm PDF fields. It provides a tree-based visualization of form structures, customizable validation rules, and an intuitive interface for quality assurance and document management workflows.

The application runs entirely in-browser with a local backend, requiring no external database or complex infrastructure—making it ideal for teams that need a simple yet powerful PDF form inspection tool.

## Key Features

- **Field Visualization**: Browse AcroForm PDF fields with detailed information about names, types, and properties
- **Custom Validation**: Define and apply naming convention rules through an intuitive UI
- **Tree Navigation**: Explore PDF structures in an organized, hierarchical view
- **Folder Organization**: Manage PDFs within custom folder structures
- **Template Management**: Create, edit, and manage validation templates directly in the application
- **Zero Configuration**: No database setup or external dependencies required
- **Cross-Platform**: Available for Windows and Linux
- **Free and Open Source**: No licensing costs or usage restrictions

## Installation

1. **Download** the executable for your operating system from the [latest release](https://github.com/tsognong/acroFormPDFAuditor/releases/tag/AcroFormPDFAuditor-v1.0.0)
2. **Extract** the package to your preferred installation directory
3. **Create** a `Files` folder in the same directory as the executable
   - This folder will store your AcroForm PDFs
   - You may organize PDFs in any subfolder structure within `Files`
4. **Launch** the application:
   - **Windows**: Double-click the executable file
   - **Linux**: Run the following command:
     ```bash
     ./AcroFormAuditor-v1.0-linux-amd64
     ```
5. **Access** the application by opening your browser and navigating to:
   ```
   http://localhost:8081
   ```

## Usage

Once the application is running, you can:

- Upload and inspect AcroForm PDF files from the `Files` folder
- Create validation templates using the built-in template editor
- Apply naming convention rules to verify field compliance
- Navigate PDF structures using the interactive tree view
- Organize and manage multiple PDF documents

Templates are automatically stored in the application's internal `Templates` folder—no manual file management required.

<img width="1299" height="738" alt="2025-11-26_14-16" src="https://github.com/user-attachments/assets/326e0b81-bb8b-4a3f-86f2-8ef4542c6c28" />


## In Production

AcroForm PDF Auditor is actively used by [**uni2grow**](https://www.uni2grow.com) as part of their IT-related PDF service workflows, supporting document processing and quality assurance operations.

## Technology Stack

- **Backend**: Go (Golang)
- **Frontend**: Single-Page Application (SPA)
- **Architecture**: Standalone web server with no external dependencies

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/tsognong/acroFormPDFAuditor/issues) or submit a pull request.

## License

This project is free app and available under the MIT License.

## Contact

**Tsognong Fidele**

- Email: [tsognong.fidele@gmail.com](mailto:tsognong.fidele@gmail.com)
- GitHub: [@tsognong](https://github.com/tsognong)
- LinkedIn: [tsognong-fidele](https://linkedin.com/in/tsognong-fidele)

---

**Note**: For the best experience, ensure your PDFs contain AcroForm fields (not XFA forms). The application is optimized for standard AcroForm inspection and validation workflows.
