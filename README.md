# Invoice

# Invoice-generator
Invoice generation is a web application. The HR of the company uses this application to send the details of the training and invoice to trainers.
HR will select the available trainer according to each training requirement. Once the details are entered by HR in the web application form and submitted, a confirmation mail along with the invoice is sent to the appointed trainer email address.

## Technologies used
* python
* Django
* HTML
* CSS

## System Model
 
 ### System Architecture
 
 ![](img/img1.png)
 
 ### E-R Diagram
 
 ![](img/img2.png)
 
## User Interface

 ![](img/img3.png)
 
## View of project

### EMAIL Functionality

In this project to send email,I performed a few Emails functionality those are as follows:

* Set up an SMTP server.
* App-specific password generation
* Retrieving trainer’s Email ID from the database
* Call the PDF Generator function and attach the PDF to the Confirmation mail.

 ![](img/img4.png)
 
### PDF Functionality

* Calling PDF generator function
* FPDF
* Fetching information from the database that has to be printed in the PDF.
* The printed information will be stored in “Invoice pdf”.
 
  ![](img/img5.png)
  
  
## Purpose of the project

I have developed this project during my academic internship program.
