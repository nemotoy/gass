# Work log

一部省略。

```sh
$ npm install -g @google/clasp
$ clasp -v
2.3.0
$ clasp login
Logging in globally...
...
Authorization successful.

Default credentials saved to: ~/.clasprc.json (/xxx/.clasprc.json).
$ clasp login --status
You are logged in as <email-address>
$ clasp logout
$ clasp login --status
You are not logged in.
$ clasp create sample
? Create which script? standalone
User has not enabled the Apps Script API. Enable it by visiting https://script.google.com/home/usersettings then retry. If you enabled this API recently, wait a few minutes for the action to propagate to our systems and retry.
$ clasp create sample
? Create which script? standalone
Created new standalone script: <URL>
Warning: files in subfolder are not accounted for unless you set a '.claspignore' file.
Cloned 1 file.
└─ appsscript.json
$ clasp pull
Warning: files in subfolder are not accounted for unless you set a '.claspignore' file.
Cloned 2 files.
└─ appsscript.json
└─ Code.js
$ clasp push -w
Watching for changed files...

Pushing files...
└─ Code.js
└─ appsscript.json
Pushed 2 files.
```
