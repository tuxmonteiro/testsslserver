# TestSSLServer
http://www.bolet.org/TestSSLServer/

TestSSLServer is a simple command-line tool which contacts a SSL/TLS server (name and port are given as parameters) and obtains some information from it:

Supported versions (among SSL 2.0, SSL 3.0, TLS 1.0, TLS 1.1 and TLS 1.2).
Support of Deflate compression (TLS-level compression, not HTTP-level gzip/deflate compression, which this tool does not consider).
Supported cipher suites, for each protocol version.
Server certificate hash and name.
