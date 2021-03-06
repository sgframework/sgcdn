# sgcdn
NodeJS Repo.


# proXject

<a href="https://www.npmjs.org/package/sgcdn" rel="nofollow"><img src="http://img.shields.io/npm/v/sgcdn.svg?style=flat" alt="NPM Version"></a> [![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/sgframework)

Ruby, NodeJS and Python PLC Development Repo.

## Node JS

Usage:

**Installation & Setup**

```bash

$ sudo apt install nodejs npm

$ npm i sgcdn

$ cd node_modules/sgcdn/bin/

$ node cmd.js

```

**Development & Commits**

```bash



```

## Python

Usage:

```bash

$ sudo apt-get install python-pip

$ pip i sgcdn

```

## Ruby

Usage:

```bash

$ sudo apt-get install ruby

$ gem i xss

```


<pre style="font-size:10px;background-color:black;"><code style="color:#ddd;" class="language-cmd">  
                              :,                            
                              :,                            
                            :.:,:,                          
                            :.:,:,                          
                          ` :.:,:,``                        
                          :`:.:,:,.:                        
                          :`:.:,:,.:                        
                          :`:.:,:,.:                        
                          ::;.:,::::                        
                          :`.::::.`:                        
                          :`  :;  `:                        
       :  :  :.           :`  ::  `:            :  :  `     
       ,:`.;. ;:          ::  :: `;:          `:, ;; :;`    
        `:, :: :;         :`::::::.:         ::` :: ;:      
       ,, :: :::,;        :` `::` `:        :::,:. ::       
        :: :; :: `;.      :`  ::  `:      `:: :; .:. ;:     
         :; :;`:  .::     ::  ::  ::     .:,  : :: .:,      
        ; ,;`.;:  , :;    :.:`::`;.:    ::`,  ::; ::        
        ::`.:;::: :  ,;   :` ,::, `:   ;;  : `;:,:; ,:      
         `::`   :;:   ::` :`  ::  `: `;;   :.:. .:;;;       
           :,    :;   , ;,;.  ::  .:::.,   ::     ;:        
            ::`::..:.``  : ;: :: :: :  ,  :;::  `:,         
             :;    `::`  :  .::::.  :  `.;,   ,;:`          
              .:`   :::  :    ;:    :  ,;`    ;:            
                ::::  :; :    :,    : :; ::: ::             
                 ::    ,::    :,    :;:    .:.              
                  :;  .:::,   :,   ,::.   :;                
                   .:::   ::  :,  :;  ::;;:                 
                  `::      ;; :, ::      :                  
             `.:;;:.::      ,::::,      ,:::.               
         .::::, :`   ::     `::;.      ::  .::;:`           
    `:::::  :`   :`   :::::::::;;:::  ::    :  ,;:::        
    .,` :`   :`   :,:::;:.   :,;   ,:::,   :    :``::::.    
    `,::::`   ::::::, `:     : ::    `::::;.   :    ::,::   
  `:::`   ::::::  ,`  :`    :,  :     :   :::::`   ::::     
     ,:::;:`  :   :   ;     ;   :,    :   ;  `:::::: `::::, 
 :::;:.   :   :   : .::    ;,    :    `,  ,   :  `::::,  `: 
 ,   `:::;,  .``:;:::`::::;:     ::::,`:::`:  .`  :` `::::. 
   .::,  : :::::`     :   ;,:   :;: `::` `:;:: :  `;::.  .;:
      ,::;:.`        ;`  `: :.  ; :`  .:     .:;:, : .::::  
      ,`            `:   :.  ; ;` ,:   :         ,::::`  .  
                    ;::::;   :::   :::,,:            ::     
                   `:   ;.:  ; ;  :::  .:                   
                   ;   `; ,`:. ,,`: :   ::                  
                  `; ``;.  ;;   ;:  ::   :                  
                  ;::`.;.  :.   :.  `;::::.                 
                 `:   :.:  :     ;  :;.  `;                 
                 :   .: `::.     : :``;   :`                
                .:.::;`  :;      `::  ;`  `:                
                ;:;:.;:  :.       ;   :::::;                
               .: : ;`:  :        `: `:: :.,:               
               ;`::.: :::`         : ;,,: ; :               
                 : ;`::::          ,;,: : :`::              
                ::.: : :`           ; ;.::.:                
                : :`::.:            ::`; : :                
                 .: : :`             : : :.,:               
                 :`:,                  ,: ;                 
                .:                      , ;`                
                                          .:           


</code></pre>


<h3 id="python"><a class="header-link" href="#python"></a><img src="{{ asset('images/assests/python.png') }}" width="70px" height="80px" /></h3>

First <a href="https://www.python.org/downloads/" target="_blank">download</a> & install <strong>Python</strong> for windows.
<br />
on Linux Terminal

<pre><code class="language-bash">   
root@0x01:~# apt-get install python
root@0x01:~# git clone https://github.com/sgframework/sgpy.git
    Cloning into 'sgpy'...
    remote: Enumerating objects: 9, done.
    remote: Counting objects: 100% (9/9), done.
    remote: Compressing objects: 100% (8/8), done.
    remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0
    Unpacking objects: 100% (9/9), done.
root@0x01:~# cd sgpy/
root@0x01:~/sgpy# ls
    LICENSE  README.md  x.py
root@0x01:~/sgpy# python x.py
    What do you want to search for ? >>
</code></pre>
<pre style="font-size:10px;background-color:black;"><code style="color:#ddd;" class="language-cmd">  

C:\Program Files\Windows Server\Bin\WebApps\Site\cdn\sgpy>python setup.py --help-commands
Standard commands:
  build             build everything needed to install
  build_py          "build" pure Python modules (copy to build directory)
  build_ext         build C/C++ extensions (compile/link to build directory)
  build_clib        build C/C++ libraries used by Python extensions
  build_scripts     "build" scripts (copy and fixup #! line)
  clean             clean up temporary files from 'build' command
  install           install everything from build directory
  install_lib       install all Python modules (extensions and pure Python)
  install_headers   install C/C++ header files
  install_scripts   install scripts (Python or otherwise)
  install_data      install data files
  sdist             create a source distribution (tarball, zip file, etc.)
  register          register the distribution with the Python package index
  bdist             create a built (binary) distribution
  bdist_dumb        create a "dumb" built distribution
  bdist_rpm         create an RPM distribution
  bdist_wininst     create an executable installer for MS Windows
  check             perform some checks on the package
  upload            upload binary package to PyPI

Extra commands:
  alias             define a shortcut to invoke one or more commands
  bdist_egg         create an "egg" distribution
  develop           install package in 'development mode'
  dist_info         create a .dist-info directory
  easy_install      Find/get/install Python packages
  egg_info          create a distribution's .egg-info directory
  install_egg_info  Install an .egg-info directory for the package
  rotate            delete older distributions, keeping N newest files
  saveopts          save supplied options to setup.cfg or other config file
  setopt            set an option in setup.cfg or another config file
  test              run unit tests after in-place build
  upload_docs       Upload documentation to PyPI

usage: setup.py [global_opts] cmd1 [cmd1_opts] [cmd2 [cmd2_opts] ...]
   or: setup.py --help [cmd1 cmd2 ...]
   or: setup.py --help-commands
   or: setup.py cmd --help


C:\Program Files\Windows Server\Bin\WebApps\Site\cdn\sgpy>
</code></pre>

