digits
======
Pycaffe + (CPU-only) DIGITS.

Usage
-----
For automatically mapping the DIGITS server port use `docker run -dP kaixhin/digits` and `docker port <id>` to retrieve the port.
For specifying the port manually use `docker run -d -p <port>:8080 kaixhin/digits`.
The shell can be entered as usual using `docker run -it kaixhin/digits bash`.