validator-nu-docker
===================

Dockerized portable standalone version of the validator.nu markup checker
from https://github.com/validator/validator.github.io

Build with:

    docker build -t myvalidator .

Run with:

    docker run -d -p 8888:8888 myvalidator

Then visit http://localhost:8888

Should give an interface similar to what's seen on http://validator.nu/

Read about the validator: http://about.validator.nu/

The API is very useful: http://wiki.whatwg.org/wiki/Validator.nu_Web_Service_Interface
