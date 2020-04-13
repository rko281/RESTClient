# REST Client for Dolphin Smalltalk 7.1
* Simple REST Request and Response handling
* Wraps IWinHttpRequest class
* Developed and tested with Dolphin Smalltalk 7.1

## Getting Started
* To download and install, evaluate the following code snippet:  
`SourceManager default fileItIn: (File readAllText: (URLMonLibrary default urlDownloadToCacheFile: 'https://raw.githubusercontent.com/rko281/RESTClient/master/install.st'))`   
* OR Download the repository to your Dolphin working directory and install the package `REST Client`  
    
Example Usage:   
    `(RESTRequest url: 'https://jsonplaceholder.typicode.com/posts') get json`
