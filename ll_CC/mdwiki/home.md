MDWiki
============================

Overview
----------------------------

Expose markdown files on GITHUB. 


Description
----------------------------

MDwiki can be hosted through GitHub.
http://dynalon.github.io/mdwiki/#!tutorials/github.md

* Step1
  - Get a GitHub account.
* Step2
  - Fork mdwiki-seed or clone it.
```bash
$ git clone https://github.com/exalted/mdwiki-seed.git
$ cd mdwiki-seed
$ git remote add wiki <clone url of the new repository>
$ git push wiki gh-pages
```

* Step3
  - Custmize sites

Note
--------------------------------
It all begins by creating an initial file structure for any language that you would like to support. You will duplicate `ll_cc` folder and rename your copy to `ja`.

`ll_cc` is a starter template folder which you should't ever edit directory, since you may loose your changes when MDwiki gets updated later.