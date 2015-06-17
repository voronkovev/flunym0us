## Introduction ##

Flunym0us is a Vulnerability Scanner for Wordpress and Moodle designed by Flu Project Team.

Flunym0us has been developed in Python. Flunym0us performs dictionary attacks against Web sites. By default, Flunym0us includes a dictionary for Wordpress and other for Moodle.

## Downloads ##

You can download the code from here (downloads tab): http://code.google.com/p/flunym0us/downloads/list

Moreover, Flunym0us is incluided in Bug-traq (Linux distribution of Audit): http://bugtraq-team.com/ (Old version)


## Operation ##

Flunym0us requires python.

Arguments allowed:

> -h, --help: Show this help message and exit

> -wp, --wordpress: Scan WordPress site

> -mo, --moodle: Scan Moodle site

> -H HOST, --host HOST: Website to be scanned

> -w WORDLIST, --wordlist WORDLIST: Path to the wordlist to use

> -t TIMEOUT, --timeout TIMEOUT: Connection timeout

> -r RETRIES, --retries RETRIES: Connection retries

> -p PROCESS, --process PROCESS: Number of process to use

> -T THREADS, --threads THREADS: Number of threads (per process) to use

## Example ##

![http://www.flu-project.com/wp-content/uploads/flunym0us2.0.png](http://www.flu-project.com/wp-content/uploads/flunym0us2.0.png)

## Versions ##

Flunym0us is distributed under the terms of GPLv3 license

ChangeLog 1.0:

> [+] Search Wordpress Plugins

> [+] Search Moodle Extensions

ChangeLog 2.0:

> [+] http user-agent hijacking

> [+] http referer hijacking

> [+] Search Wordpress Version

> [+] Search Wordpress Latest Version

> [+] Search Version of Wordpress Plugins

> [+] Search Latest Version of Wordpress Plugins

> [+] Search Path Disclosure Vulnerabilities

> [+] Search Wordpress Authors

## Authors ##

- Juan Antonio Calles (@jantonioCalles)

- Pablo Gonzalez (@fluproject)

- Chema Garcia (@sch3m4)

- German Sanchez (@enelpc)