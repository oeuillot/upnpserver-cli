# upnpserver-cli

Command line for [upnpserver](https://github.com/oeuillot/upnpserver).

## Installation

    $ npm install upnpserver-cli -g

## Help

```
 $ upnpserver --help

  Usage: upnpserver [options]

  Options:

    -h, --help              output usage information
    -V, --version           output the version number
    -d, --directory <path>  Mount directory
    -m, --music <path>      Mount music directory
    -n, --name <name>       Name of server
    -u, --uuid <uuid>       UUID of server
    --dlna                  Enable dlna support
    --lang <lang>           Specify language (en, fr)
    -p, --httpPort <port>   Http port

```

## Example

```  

 $ upnpserver -d /MyFilms=/data/MyFilms -d /PublicVideo=/home/me/videos -m /Musiques=/home/Musiques -n "My server" 

 ```
 

## Author

Olivier Oeuillot
