Repo to reproduce bug.

Steps:
```sh
$ meteor # won't work
# While Building the application:
# meteor-bootstrap-sass-bug.sass: Scss compiler error: undefined
#/tmp/meteor-bootstrap-sass-bug/meteor-bootstrap-sass-bug.sass:1: error: file to import not found or unreadable: ".meteor/local/build/programs/server/assets/packages/reywood_bootstrap3-sass/_bootstrap"

^C
$ meteor # will work
^C
$ meteor reset
$ meteor # won't work
# While Building the application:
# meteor-bootstrap-sass-bug.sass: Scss compiler error: undefined
#/tmp/meteor-bootstrap-sass-bug/meteor-bootstrap-sass-bug.sass:1: error: file to import not found or unreadable: ".meteor/local/build/programs/server/assets/packages/reywood_bootstrap3-sass/_bootstrap"
^C
$ meteor # will work
```

