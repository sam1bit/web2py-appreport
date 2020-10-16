web2py-appreport is a plugin for web2py, it was designed to help the generation of PDF reports.

- screencast: http://vimeo.com/18601633
- wiki for documentations and examples: https://github.com/lucasdavila/web2py-appreport/wiki 

[![endorse](http://api.coderwall.com/lucasdavila/endorsecount.png)](http://coderwall.com/lucasdavila)
Thank you

## CHANGE LOG

0.0.2
- Updated appreport module, because was included a new engine (called Pisa) to build the PDF documents, for more information visit: http://www.xhtml2pdf.com/
- Changed de helper REPORT to set default Pisa as engine to build PDF documents.
- Included a example to create complex reports, rendering a web2py views in PDF document, using the appreport plugin.

0.1.0
- Updated appreport lib to version v0.1.0, and moved to this project modules and classes specific of web2py framework.
- Implemented news helpers REPORTPISA and REPORTPYFPDF.
- Added a new example to remote reports using xmlrpc.
- Changed structure of plugin in directory modules/plugin_appreport, and more updates.
