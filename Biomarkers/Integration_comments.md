## **Comments and recommendations for functional-release-final version**

Congratulations on getting your functional module assembled! The next step in the development process is to integrate the module into NIH Cloud Lab. To accomplish that, we will be providing feedback and recommendations on certain aspects of the module in order to get it ready to go live on Cloud Lab. Below are some comments we believe will make the module stronger. Feel free to reach out with any questions.

### **Best practices**
* Store data in a bucket instead of repository. 
* To set up your project and notebooks, we recommend just referring to these cloud lab documents, https://github.com/STRIDES/NIHCloudLabGCP/blob/main/docs/open_GCP_project.md for opening  and finding a GCP project, and then this one for creating a Vertex AI notebook https://github.com/STRIDES/NIHCloudLabGCP/blob/main/docs/vertexai.md. You can specify the machine type and cpus etc but just point them to these existing docs.
* Make sure to remove all outputs from notebooks. This is done through Edit -> Clear All Outputs"
### **Knowledge checks**
Quizzes are not displayed. The code block shows but no interactive quiz form.
### **Graphics**
(No Action Required) Graphics are by far the best of any module I've seen.
### **README file**
* It is unclear why "BioConductor" is bolded in Software Requirements.
* Update information to download tutorial content from github (final host github TBD, currently says "gcloud source repos clone nosi-uri-biomarker --project=nosi-uri-biomarker-4148")
* Included information on submodules 7-9
### **508-compliant videos**
No videos included in module, one video should be planned/included.
### **Technical implementation design documents**
* Add submodules 7-9 once the notebooks are finished.
* (No Action Required) TID diagram is present and legible in the README. 
### **File naming conventions**
(No Action Required) Files are consistently named with logical conventions throughout
### **Module readability and flow**
* Submodule 2, Should first install library(""tidyverse"") library(""magrittr""); 
* Submodule 3 has a `Note to self` still embedded.
* Submodule 3 ""heteroscdastic"" should be ""heteroscedastic""
* Submodule 3 ""he intercept"" should be ""The intercept""
* Submodule 2 ""depeleted"" should be ""depleted""
* Do a proof read for spelling and grammer. Content looks great, there are just a couple of syntax things throughout.
* The ""The End"" at the end of submodule 5 should be moved when you finish the other notebooks"
* Need to work on/complete Submodules 7-9
### **Directory structure and organization**
* Move everything from within the Biomarkers dir out to the base dir rather than having everything inside an additional folder.
* Data should be stored and pulled from a bucket with bucket creation step. Can include a link to Deloitte made how to documents.
### **Paths and links**
(No Action Required) Valid
### **Scientific completeness**
(No Action Required) Very good