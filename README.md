# swingrestapis

## Set up the GitHub Pages

* Go to the organization page, https://github.com/minkonet.
* Create a repository, *swingrestapis*.
* Create a branch, *gh-pages*.
* Push the manual to the branch.
* Open https://minkonet.github.io/swingrestapis to see what has been published.

## Generate a manual

*Apidoc* is used to generate the manual. Run this command to generate an API refernece manual. Refer the 'apidoc.json' for the configuration.

> apidoc -i ../swingserver/mgmtserver/v0/routes -f gamers.js -o . 


