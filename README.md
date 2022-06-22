# Certs! Why did it have to be certs?

Getting certs right when setting up a new test environment is a painful
business. This script automates the process so you can setup your PKI and tear
it down again quickly.

You'll need to create a lib/passwords file and put each of the cert passwords
in there to make this work.

## Acknowledgements

This is massively cribbed from this excellent
[guide](https://jamielinux.com/docs/openssl-certificate-authority/index.html)
