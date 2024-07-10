# 1001 - Management of documents

## Process description
This process describes how documents are managed in the 'Symptom Solver' software group. It includes the creation, review, approval, distribution, and control of documents. The purpose of this process is to ensure that documents are available where needed, are kept up to date, and that obsolete documents are removed.
All documents are stored in the 'Symptom Solver' software group's GIT repository, which is accessible to all members of the group. The documents are written in markdown format and are version controlled using GIT. The current version of the document lays in the master branch of the GIT repository. 

To create a new document first make a copy of the template document stored in the GIT repository. Fill in the respecting fields of the template document. Once finished create a new branch in the GIT repository, save the newly created document and create a pull request to merge the changes into the master branch

To change an existing document first make a copy of the existing document, then make the desired changes. If not for good reason the structure should not be changed from the one inherited from the Template. Once finished create a new branch in the GIT repository, save the adapted version of the existing document. If a new structure was implemented, descripe the reasoning in the commit message. Then create a pull request to merge the changes into the master branch.



### Creation of new documents
When a new document needs to be created, the author should copy the template document from the 'Symptom Solver' software group's GIT repository and fill in the different sections of the document. The author should then create a new branch in the GIT repository, make the changes, and create a pull request to merge the changes into the master branch. 
The pull request should be reviewed by at least one member of the 'Symptom Solver' software groups leadership board before it is merged into the master branch. The detailed review process is described in the '1002 - Management review of quality management system documents' document. It is important, that the name of the document follows the naming convention which is described in the following: 
    
    ```
    OrderNumber-DocumentName.md
    ```
Also, the document needs to be added to the Table of Contents in the QM Manual.

## Process inputs
* Template document

## Process outputs
* New or updated document

## Responsible
CEO

## Involved
All members of the 'Symptom Solver' software group

## Frequency
When a new document needs to be created or an existing document needs to be updated.

## Interfaces to other processes
Input to the '1002 - Management review of the quality management system' process.

## Monitoring and control
The process is monitored by the CEO who is responsible for ensuring that all documents are up to date and that obsolete documents are removed. The CEO reviews the GIT repository once a month to check for new documents or updates to existing documents. If a document is found to be out of date, the CEO will assign a member of the 'Symptom Solver' software group to update the document. The CEO also reviews the Table of Contents in the QM Manual to ensure that all documents are listed. If a document is missing from the Table of Contents, the CEO will assign a member of the 'Symptom Solver' software group to add the document. 
Additionally, the CEO monitores, that no changes are made to the master branch without a pull request and reviewed as described in the '1002 - Management review of quality management system documents' process.