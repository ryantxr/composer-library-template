Composer Library Template
=========================

If you are trying to create a new PHP Composer library, whether it will be going to submitted to packagist.org or just in your Github account, this template of files will surely help you make the process a lot easier and faster.

Features
--------

* PSR-4 autoloading compliant structure
* Unit-Testing with PHPUnit
* Comprehensive Guides and tutorial
* Easy to use to any framework or even a plain php file

Usage
-----

* Clone the repo.
* Disconnect it from the remote GIT repo
    - rm -rf .git
* Initialize a new GIT repo
    - git init
* Do a search and replace of "MyNamespace" to whatever namespace you want to use.
* Update the namespace and info in composer.json
* Rename YourClass.php and YourClassTest.php to some name that makes sense for you.
* Update this README.
* Add all files to the new repo
    - git add . && git commit -m'initial'
* Push the repo to a new remote repo if you want.
