---
title: README
---

This Repository is the source for the [website](//rcsanantonio.github.io) for the Regnum Christi San Antonio Locality.

The website is based on Jekyll and can be maintain locally by installing it on your machine.

## To Install Jekyll on Windows
1 - Go here: https://jekyllrb.com/docs/installation/windows/
    It says:
	1.1 - Download and install a Ruby+Devkit version from RubyInstaller Downloads. (https://rubyinstaller.org/downloads/) Use default options for installation.
	1.2 - Run the ridk install step on the last stage of the installation wizard and select:
             + MSYS2 and MINGW development tool chain
      1.3 - Install Jekyll and Bundler using 
             > gem install jekyll bundler
      1.4 - Check if Jekyll has been installed properly: 
             > jekyll -v

2 - Since 'webrick' is not part of ruby any more, you'll have to install webrick on your machine by hand.  On the command line (once ruby has been installed) type:
    > bundle add webrick


## To use the local Jekyll engine:

### Start Jekyll markdown/server
To view help you can use like this:
    C:\Source\AsnaQSys\asnaqsys.github.io>bundle exec jekyll serve
or with Incremental transformation like this:
    C:\Source\AsnaQSys\asnaqsys.github.io>bundle exec jekyll serve --incremental


### To visit the local site enter on your browser:
	http://127.0.0.1:4000


### Update TOC
After editing the toc.yaml file, it is necessary to 'touch' the file that 'jsonify' it
    js\toc.json