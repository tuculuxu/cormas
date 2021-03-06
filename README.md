This is an ongoing effort to port CORMAS to Pharo ecosystem: http://www.pharo.org/
Current stable version of CORMAS is based on VisualWorks 7.6 and can be found on: http://cormas.cirad.fr/indexeng.htm

:bangbang: Current active development repository is located at **[SmalltalkHub](http://www.smalltalkhub.com/#!/~SergeStinckwich/CORMAS)**

Some documentation (to be cleaned and reorganized) about Cormas is available on the Wiki here: 
https://github.com/cormas/documentation

All issues about the current and ongoing port are here: https://github.com/cormas/cormas/issues

##How to install Cormas in MOOSE 5.0 image

Download last version of MOOSE 5.0 here: http://www.moosetechnology.org/

If you want to install the last stable version (0.1):
```Smalltalk
Gofer new
   url: 'http://smalltalkhub.com/mc/SergeStinckwich/CORMAS/main';
   package: 'ConfigurationOfCormas';
   load.
((Smalltalk at: #ConfigurationOfCormas) project version: '0.1') load.
```

If you want to install the development version:
```Smalltalk
Gofer new
url: 'http://smalltalkhub.com/mc/SergeStinckwich/CORMAS/main';
   package: 'ConfigurationOfCormas';
   load.
(Smalltalk at: #ConfigurationOfCormas) loadDevelopment.
```

All packages load into the Cormas-* package names.

## Licence
Cormas is licensed under MIT. See : http://opensource.org/licenses/MIT

## How to contribute to CORMAS

We welcome submissions! A google group exists for this project at http://groups.google.com/group/cormas-dev
