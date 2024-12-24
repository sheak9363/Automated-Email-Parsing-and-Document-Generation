# Automated Email Parsing and Document Generation System

## Overview
This system automates the process of receiving input documents via email, extracting and processing their contents, and returning a budget estimation as both an Excel file and a PDF to the sender. The system is designed to handle distorted or incomplete data, consolidate it into a coherent format, and generate cost sheets effectively.

---

## Features
1. **Email Integration**:
   - Automatically receives emails with attached input documents.
   - Replies to the sender with processed outputs.

2. **Data Parsing and Processing**:
   - Reads and parses attached PDF files.
   - Converts extracted data into Excel (.xlsx) and PDF formats.
   - Consolidates distorted data into a unified Excel sheet.

3. **Cost Sheet Generation**:
   - Generates cost sheets based on input data.
   - Outputs cost sheet in both Excel and PDF formats.

4. **Automation**:
   - Fully automated workflow from email reception to response.

---

## Workflow
1. **Receiving Input**:
   - The system monitors the mailbox for incoming emails with attachments.
   - It reads the sender’s email ID and downloads the attached documents.

2. **Data Extraction and Processing**:
   - Extracts text and data from attached PDF files.
   - Consolidates data into a single Excel sheet.
   - Generates a detailed cost sheet.

3. **Output Generation**:
   - Creates processed output documents in Excel and PDF formats.

4. **Sending Response**:
   - Sends the processed documents back to the sender as email attachments.

---

## Installation  
### Prerequisites  
1. Python 3.x installed on your system.  
2. mongoDB installed and configured with user credentials.  

### Steps to Run  
1. Clone the repository:  
   ```bash  
   git clone <repository-url>  
   cd Automated-Email-Parsing-and-Document-Generation    

2. Set up the database:
   - Create mongoDB collections accordingly.

   
## Usage
1. Send an email with a PDF document attached to the configured mailbox.
2. The system will process the input and reply with the generated cost sheet in Excel and PDF formats..
3. Launch the application.

## Future Enhancements
- Support for additional file formats (e.g., Word, CSV).
- Improved data validation and error handling.
- Integration with cloud storage services.
- Enhanced user interface for monitoring and configuration.

## License
   This project is licensed under the **MIT License**.

## Contact
For any inquiries or suggestions, please contact:

Email: [alifnisha89295@gmail.com]

GitHub: [(https://github.com/sheak9363)]

