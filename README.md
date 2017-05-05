# HRCloud2-Client
A cross-platform desktop client for the HRCloud2 Platform.

### This repo was forked from https://github.com/jacklam718/ftp !!! Thank you!

## A WIP cross-platform Client (Upload/Download) for the HRCloud2 Platform

The HRCloud2-Client App was ported from Gihub user Jacklam718/ftp on 5/3/2017. 

It is a slightly modified (as-of-yet) version of the original, compiled to .exe for cross-platform support from interpreted Python to a compiled binary that can be run on many platforms with PyInstaller.

The intention for this project will be:

1. To modify the original application to use SFTP and custom user-specific HRCloud2 API keys for user auth and file transfer..
2. To enable the original application to work on multiple desktop platforms with minimal dependency requirements.
3. To enable the original application to sync files between locations. Possibly create Windows tasks and/or cron's to automate these for the user.
4. To enable the original application to use custom CuRL requests to perform HRC2 cloudCore ops (convert, arch, dearch, rename, PDFwork, ect...) on local and remote user files through the server.
5. Log all important activities. 
6. Perform all required tasks with standard user permissions and protocol practices that won't get developers fired. 

Stay-tuned for updates that enable functionality!

### If you encounter "Access Denied" select to "Run As Administrator" or double-check that permissions are "0755".

![HRCloud2-Client(Ported)](https://raw.githubusercontent.com/zelon88/HRCloud2-Client/35d7671371af0984c6ec53b843ba9618b895ec5a/src/ftpClient/Resources/Screenshote/HRCloud2-Client(Ported).png)
