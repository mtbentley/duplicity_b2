*NOTE: THIS IS OFFICIALLY INTEGRATED INTO DUPLICITY. PLEASE REPORT BUGS THERE ON 
THEIR LAUNCHPAD*

https://bugs.launchpad.net/duplicity/+bugs

A duplicity backend for BackBlaze’s B2 storage service.

To install, copy to `/usr/lib/python2.7/site-packages/duplicity/backends`

Run with `duplicity /local/folder/ b2://account_id@bucket_name/`

When it asks for you password, enter your application key

If you don’t want it to prompt you for the key, run with 
`FTP_PASSWORD=application_key duplicity /local/folder b2://account_id@bucket_name/`

Note: requires duplicity 0.7+ and python 2.7. Older versions of Ubuntu and Homebrew have older,
incompatible versions of duplicity and possibly python.
