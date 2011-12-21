# phpa-norl
PHP shell for Mac OS X and Windows

* **Homepage:** <http://www.fischerlaender.net/php/phpa-norl>

## License
phpa-norl is, like the original phpa, public domain. Feel free to do with it whatever you want.

## Install
1. `$ git clone https://github.com/jmagnusson/phpa-norl.git`
2. `$ mv ./phpa-norl/phpa-norl /usr/local/bin`
3. `$ rm -rf ./phpa-norl`

## How-To
1. `$ phpa-norl`

If you get `-bash: phpa-norl: command not found` you probably need to add `/usr/local/bin/` to the path environment variable. Add it with:

1. `echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.profile``
2. `source ~/.profile`
