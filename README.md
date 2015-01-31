KnProxy
============

KnProxy is a lightweight, PHP-based web proxy that uses either cURL or PHP Sockets to proxy HTTP/HTTPS connections on a remote machine. 
It was created to achieve a high compatibility and ease of deployment and serves as a means to bypass the China GFW. 

It should work out of the box without modifications, though you can fine tune it to fit your specific needs.
Aside from the connecting ability module (which requires at least one of cURL, PHP Sockets or remote file reading to be available), KnProxy
does not rely on any other additional PHP extensions (Although optional page compression requires the compression module for PHP to be enabled). 
KnProxy includes a document parser, url parser and session management module all self contained.

