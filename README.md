# What is DV_Standalone
DV_Standalone is Electronic Signature Document (PDF) Validation, Run via Microsoft cammand line, with .Net Framwork 4.6 later

# How to use this program
By run on Command Prompt> DV_Standalone.exe /ds=PDFSourceDirectory /dd=PDFDestinationDirectory

# Example Run Step
0. Copy DV_Standalone.exe to path that you want, eg. C:\Certificate
1. Prepare PDF files on PDFSourceDirectory eg. C:\Certificate\PDF_Source
2. Prepare Directory for output of PDF was Validation checked. (or If you not created Path, Program will be create by it self.)
3. Open Command Prompt and goto program path eg. C:\Certificate (at step-0)
4. Run command eg. C:\Certificate> DV_Standalone.exe /ds=C:\Certificate\PDF_Source /dd=C:\Certificate\PDF_Validate
   4.1 Program will load each PDF file from C:\Certificate\PDF_Source
   4.2 Program will check electronic signature on each PDF file
       4.2.1 PDF is Valid will copy to C:\Certificate\PDF_Validate\Valid
       4.2.2 PDF is Invalid will copy to C:\Certificate\PDF_Validate\invalid
       4.2.3 PDF is not have any signature will copy to C:\Certificate\PDF_Validate\NoSign

# This program will be expire on 31 December 2024
You can contact to Patrapee.S@en.rmutt.ac.th to renew the program.
