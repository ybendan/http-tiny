http-tiny 1.2 fork support for POST and Basic auth

http-tiny is good implementation of HTTP for embedded 
applications.

For support basic auth you should be implement your own
function for base64 encoding or use another one, see
http\_set\_base64\_encoder.

- http\_post added
- http\_set\_basic\_auth added

TODO

- Making library thread-safe.
- Improve code style.
- Update manual pages.
