ROR_Wiki
========

Ruby On Rails Development on Windows Wiki notes

# How to setup cURL on Windows 7 64-bit
Setup cURL on Windows 7 64-bit
Setup cURL:

	1.Download and unzip 64-bit cURL with SSL: http://curl.download.nextag.com/download/curl-7.21.7-win64-ssl-sspi.zip  
	2.Copy the curl.exe file into your Windows PATH folder. By default, this is C:\Windows\System32.
	3.Download and install the Visual Studio 2010 C++ Runtime Redistributable 64 bit here: http://www.microsoft.com/download/en/details.aspx?id=13523
	4.Download the latest bundle of Certficate Authority Public Keys from mozilla.org: http://curl.haxx.se/ca/cacert.pem
	5.Rename this file from cacert.pem to curl-ca-bundle.crt.
	6.Move this file into your Windows PATH folder. By default, this is C:\\Windows\System32.
	
Test it:

	1.Run cmd.exe to open your command prompt.
	2.type curl -L http://www.google.com
	3.type curl -L https://www.google.com
For both commands, you should see a couple pages of the HTML source code. If you see this, cURL is up and running!

