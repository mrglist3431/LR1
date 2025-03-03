# LR1
─(kali㉿kali)-[~]
└─$ # tip: check development environment
$ cmake --version
$ curl --version
$ git --version
$ g++ --version
$ hub --version
$ make --version
$ subl --version
$ tree --version
$ wget --version
$ openssl version
$: command not found
$: command not found
$: command not found
$: command not found
$: command not found
$: command not found
$: command not found
$: command not found
$: command not found
$: command not found
                                                                             
┌──(kali㉿kali)-[~]
└─$ cmake --version
Command 'cmake' not found, but can be installed with:
sudo apt install cmake
Do you want to install it? (N/y)y
sudo apt install cmake
[sudo] password for kali: 
Installing:                     
  cmake

Installing dependencies:
  cmake-data  libjsoncpp26  librhash1
                                                                             
Suggested packages:
  cmake-doc  cmake-format  elpa-cmake-mode  ninja-build

Summary:
  Upgrading: 0, Installing: 4, Removing: 0, Not Upgrading: 1344
  Download size: 13.8 MB
  Space needed: 52.4 MB / 446 GB available

Continue? [Y/n] y
Get:1 http://kali.download/kali kali-rolling/main amd64 cmake-data all 3.30.5-1 [2,223 kB]
Get:2 http://kali.download/kali kali-rolling/main amd64 libjsoncpp26 amd64 1.9.6-3 [81.7 kB]
Get:3 http://kali.download/kali kali-rolling/main amd64 librhash1 amd64 1.4.5-1 [132 kB]
Get:4 http://kali.download/kali kali-rolling/main amd64 cmake amd64 3.30.5-1 [11.4 MB]
Fetched 13.8 MB in 12s (1,166 kB/s)                                         
Selecting previously unselected package cmake-data.
(Reading database ... 400166 files and directories currently installed.)
Preparing to unpack .../cmake-data_3.30.5-1_all.deb ...
Unpacking cmake-data (3.30.5-1) ...
Selecting previously unselected package libjsoncpp26:amd64.
Preparing to unpack .../libjsoncpp26_1.9.6-3_amd64.deb ...
Unpacking libjsoncpp26:amd64 (1.9.6-3) ...
Selecting previously unselected package librhash1:amd64.
Preparing to unpack .../librhash1_1.4.5-1_amd64.deb ...
Unpacking librhash1:amd64 (1.4.5-1) ...
Selecting previously unselected package cmake.
Preparing to unpack .../cmake_3.30.5-1_amd64.deb ...
Unpacking cmake (3.30.5-1) ...
Setting up libjsoncpp26:amd64 (1.9.6-3) ...
Setting up cmake-data (3.30.5-1) ...
Setting up librhash1:amd64 (1.4.5-1) ...
Setting up cmake (3.30.5-1) ...
Processing triggers for libc-bin (2.40-3) ...
Processing triggers for man-db (2.13.0-1) ...
Processing triggers for kali-menu (2024.4.0) ...
                                                                             
┌──(kali㉿kali)-[~]
└─$ git --version
git version 2.45.2
                                                                             
┌──(kali㉿kali)-[~]
└─$ g++ --version
g++ (Debian 14.2.0-8) 14.2.0
Copyright (C) 2024 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

                                                                             
┌──(kali㉿kali)-[~]
└─$ hub --version
Command 'hub' not found, but can be installed with:
sudo apt install hub
Do you want to install it? (N/y)y
sudo apt install hub
Installing:                     
  hub
                                                                             
Installing dependencies:
  xsel
                                                                             
Summary:
  Upgrading: 0, Installing: 2, Removing: 0, Not Upgrading: 1344
  Download size: 2,378 kB
  Space needed: 7,306 kB / 446 GB available

Continue? [Y/n] y
Get:1 http://http.kali.org/kali kali-rolling/main amd64 hub amd64 2.14.2~ds1-1+b18 [2,358 kB]
Get:2 http://kali.download/kali kali-rolling/main amd64 xsel amd64 1.2.1-1 [19.9 kB]
Fetched 2,378 kB in 2s (1,348 kB/s)
Selecting previously unselected package hub.
(Reading database ... 403673 files and directories currently installed.)
Preparing to unpack .../hub_2.14.2~ds1-1+b18_amd64.deb ...
Unpacking hub (2.14.2~ds1-1+b18) ...
Selecting previously unselected package xsel.
Preparing to unpack .../xsel_1.2.1-1_amd64.deb ...
Unpacking xsel (1.2.1-1) ...
Setting up xsel (1.2.1-1) ...
Setting up hub (2.14.2~ds1-1+b18) ...
Processing triggers for man-db (2.13.0-1) ...
Processing triggers for kali-menu (2024.4.0) ...
                                                                             
┌──(kali㉿kali)-[~]
└─$ make --version
GNU Make 4.3
Built for x86_64-pc-linux-gnu
Copyright (C) 1988-2020 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
                                                                             
┌──(kali㉿kali)-[~]
└─$ subl --version
Command 'subl' not found, did you mean:
  command 'subs' from deb libsubtitles-perl
Try: sudo apt install <deb name>
                                                                             
┌──(kali㉿kali)-[~]
└─$ sudo apt install subl
Error: Unable to locate package subl
                                                                             
┌──(kali㉿kali)-[~]
└─$ tree --version
tree v2.1.3 © 1996 - 2024 by Steve Baker, Thomas Moore, Francesc Rocher, Florian Sesser, Kyosuke Tokoro
                                                                             
┌──(kali㉿kali)-[~]
└─$ wget --version
GNU Wget 1.24.5 built on linux-gnu.

-cares +digest -gpgme +https +ipv6 +iri +large-file -metalink +nls 
+ntlm +opie +psl +ssl/gnutls 

Wgetrc: 
    /etc/wgetrc (system)
Locale: 
    /usr/share/locale 
Compile: 
    gcc -DHAVE_CONFIG_H -DSYSTEM_WGETRC="/etc/wgetrc" 
    -DLOCALEDIR="/usr/share/locale" -I. -I../../src -I../lib 
    -I../../lib -Wdate-time -D_FORTIFY_SOURCE=2 
    -I/usr/include/p11-kit-1 -DHAVE_LIBGNUTLS -DNDEBUG -g -O2 
    -Werror=implicit-function-declaration 
    -ffile-prefix-map=/build/reproducible-path/wget-1.24.5=. 
    -fstack-protector-strong -fstack-clash-protection -Wformat 
    -Werror=format-security -fcf-protection -DNO_SSLv2 
    -D_FILE_OFFSET_BITS=64 -g -Wall 
Link: 
    gcc -I/usr/include/p11-kit-1 -DHAVE_LIBGNUTLS -DNDEBUG -g -O2 
    -Werror=implicit-function-declaration 
    -ffile-prefix-map=/build/reproducible-path/wget-1.24.5=. 
    -fstack-protector-strong -fstack-clash-protection -Wformat 
    -Werror=format-security -fcf-protection -DNO_SSLv2 
    -D_FILE_OFFSET_BITS=64 -g -Wall -Wl,-z,relro -Wl,-z,now -lpcre2-8 
    -luuid -lidn2 -lnettle -lgnutls -lz -lpsl ../lib/libgnu.a 

Copyright (C) 2015 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later
<http://www.gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Originally written by Hrvoje Niksic <hniksic@xemacs.org>.
Please send bug reports and questions to <bug-wget@gnu.org>.
                                                                             
┌──(kali㉿kali)-[~]
└─$ openssl --version
OpenSSL 3.3.2 3 Sep 2024 (Library: OpenSSL 3.3.2 3 Sep 2024)
                                                                             
┌──(kali㉿kali)-[~]
└─$ echo TOKEN(ON U MENYA YEST NO GIT NE DAET SOXRANIT) < h
zsh: no such file or directory: h
                                                                             
┌──(kali㉿kali)-[~]
└─$ echo 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 < desktop
zsh: no such file or directory: desktop
                                                                             
┌──(kali㉿kali)-[~]
└─$ ls                                                     
Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos
                                                                             
┌──(kali㉿kali)-[~]
└─$ echo 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 < Desktop
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
                                                                             
┌──(kali㉿kali)-[~]
└─$ lah
lah: command not found
                                                                             
┌──(kali㉿kali)-[~]
└─$ ls -lah
total 136K
drwx------ 16 kali kali 4.0K Feb 26 09:47 .
drwxr-xr-x  3 root root 4.0K Feb 25 08:02 ..
-rw-r--r--  1 kali kali  220 Feb 25 08:02 .bash_logout
-rw-r--r--  1 kali kali 5.5K Feb 25 08:02 .bashrc
-rw-r--r--  1 kali kali 3.5K Feb 25 08:02 .bashrc.original
drwxrwxr-x 10 kali kali 4.0K Mar  3 04:02 .cache
drwxr-xr-x 13 kali kali 4.0K Mar  3 04:21 .config
drwxr-xr-x  2 kali kali 4.0K Mar  3 04:21 Desktop
-rw-r--r--  1 kali kali   35 Feb 25 11:03 .dmrc
drwxr-xr-x  2 kali kali 4.0K Feb 25 11:03 Documents
drwxr-xr-x  2 kali kali 4.0K Feb 25 11:03 Downloads
-rw-r--r--  1 kali kali  12K Feb 25 08:02 .face
lrwxrwxrwx  1 kali kali    5 Feb 25 08:02 .face.icon -> .face
drwx------  3 kali kali 4.0K Feb 25 11:03 .gnupg
-rw-------  1 kali kali    0 Feb 25 11:03 .ICEauthority
drwxr-xr-x  3 kali kali 4.0K Feb 25 08:02 .java
drwxr-xr-x  5 kali kali 4.0K Feb 25 11:03 .local
drwx------  4 kali kali 4.0K Feb 25 08:04 .mozilla
drwxr-xr-x  2 kali kali 4.0K Feb 25 11:03 Music
drwxr-xr-x  2 kali kali 4.0K Feb 25 11:03 Pictures
-rw-r--r--  1 kali kali  807 Feb 25 08:02 .profile
drwxr-xr-x  2 kali kali 4.0K Feb 25 11:03 Public
-rw-r--r--  1 kali kali    0 Feb 25 08:05 .sudo_as_admin_successful
drwxr-xr-x  2 kali kali 4.0K Feb 25 11:03 Templates
drwxr-xr-x  2 kali kali 4.0K Feb 25 11:03 Videos
-rw-------  1 kali kali   49 Feb 26 09:47 .Xauthority
-rw-------  1 kali kali 4.8K Mar  3 04:17 .xsession-errors
-rw-------  1 kali kali 5.9K Feb 25 09:58 .xsession-errors.old
-rw-r--r--  1 kali kali  336 Feb 25 08:02 .zprofile
-rw-------  1 kali kali    0 Feb 25 09:51 .zsh_history
-rw-r--r--  1 kali kali  11K Feb 25 08:02 .zshrc
                                                                             
┌──(kali㉿kali)-[~]
└─$ export GITHUB_USERNAME=mrglist3431       
                                                                             
┌──(kali㉿kali)-[~]
└─$ export GIST_TOKEN=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
                                                                             
┌──(kali㉿kali)-[~]
└─$ alias edit=<nano|vi|vim|subl>
zsh: parse error near `\n'
                                                                             
┌──(kali㉿kali)-[~]
└─$ alias edit=nano              
                                                                             
┌──(kali㉿kali)-[~]
└─$ alias edit=nano|vi|vim|subl
Vim: Warning: Output is not to a terminal
Vim: Warning: Output is not to a terminal
Vim: Warning: Input is not from a terminal
Vim: Warning: Input is not from a terminal
Command 'subl' not found, did you mean:
  command 'subs' from deb libsubtitles-perl
Try: sudo apt install <deb name>
                                                                             
┌──(kali㉿kali)-[~]
                   └─$ 
                                                                             
┌──(kali㉿kali)-[~]
                   └─$ 
                                                                             
┌──(kali㉿kali)-[~]
                   └─$ 22
22: command not found
                                                                                                  
┌──(kali㉿kali)-[~]
                   └─$ mkdir -p ${GITHUB_USERNAME}/workspace
                                                                             
┌──(kali㉿kali)-[~]
                   └─$ cd ${GITHUB_USERNAME}/workspace
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ pwd
/home/kali/mrglist3431/workspace
                                                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ cd ..                          
                                                                             
┌──(kali㉿kali)-[~/mrglist3431]
                               └─$ pwd
/home/kali/mrglist3431
                                                                                                   
┌──(kali㉿kali)-[~/mrglist3431]
                               └─$ mkdir -p workspace/tasks/
                                                                             
┌──(kali㉿kali)-[~/mrglist3431]
                               └─$ mkdir -p workspace/projects/
                                                                             
┌──(kali㉿kali)-[~/mrglist3431]
                               └─$ mkdir -p workspace/reports/
                                                                             
┌──(kali㉿kali)-[~/mrglist3431]
                               └─$ cd workspace
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ wget https://nodejs.org/dist/v6.wget https://nodejs.org/dist/v6.11.5/node-v6.11.5-linux-x64.tar.xz
--2025-03-03 04:34:14--  https://nodejs.org/dist/v6.11.5/node-v6.11.5-linux-x64.tar.xz
         Resolving nodejs.org (nodejs.org)... 104.20.22.46, 104.20.23.46, 2606:4700:10::6814:172e, ...
                         Connecting to nodejs.org (nodejs.org)|104.20.22.46|:443... connected.
                 HTTP request sent, awaiting response... 200 OK
                                                               Length: 9356460 (8.9M) [application/x-xz]
                           Saving to: ‘node-v6.11.5-linux-x64.tar.xz’

node-v6.11.5-linux- 100%[================>]   8.92M  1.19MB/s    in 7.5s    

                                                                            2025-03-03 04:34:22 (1.20 MB/s) - ‘node-v6.11.5-linux-x64.tar.xz’ saved [9356460/9356460]

                                                                                        
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ tar -xf node-v6.11.5-linux-x64.ttar -xf node-v6.11.5-linux-x64.tar.xz
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ rm -rf node-v6.11.5-linux-x64.tarm -rf node-v6.11.5-linux-x64.tar.xz
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ mv node-v6.11.5-linux-x64 node
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ ls node/bin
node  npm
                                                                                      
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ echo ${PATH}
/home/kali/.local/bin:/usr/local/sbin:/usr/sbin:/sbin:/usr/local/bin:/usr/bin:/bin:/usr/local/games:/usr/games:/home/kali/.dotnet/tools
                                                                                                                                       
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ export PATH=${PATH}:`pwd`/node/bexport PATH=${PATH}:`pwd`/node/bin
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ echo ${PATH}
/home/kali/.local/bin:/usr/local/sbin:/usr/sbin:/sbin:/usr/local/bin:/usr/bin:/bin:/usr/local/games:/usr/games:/home/kali/.dotnet/tools:/home/kali/mrglist3431/workspace/node/bin
                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ mkdir scripts
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ cat > scripts/activate<<EOF
heredoc> export PATH=\${PATH}:`pwd`/node/bin
heredoc> EOF
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ source scripts/activate
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ gem install gist
Fetching gist-6.0.0.gem
                       ERROR:  While executing gem ... (Gem::FilePermissionError)
        You don't have write permissions for the /var/lib/gems/3.1.0 directory.
        /usr/lib/ruby/vendor_ruby/rubygems/installer.rb:713:in `verify_gem_home'
        /usr/lib/ruby/vendor_ruby/rubygems/installer.rb:903:in `pre_install_checks'
        /usr/lib/ruby/vendor_ruby/rubygems/installer.rb:303:in `install'
                                                                            /usr/lib/ruby/vendor_ruby/rubygems/resolver/specification.rb:105:in `install'
                                                                            /usr/lib/ruby/vendor_ruby/rubygems/request_set.rb:195:in `block in install'
                                                                            /usr/lib/ruby/vendor_ruby/rubygems/request_set.rb:183:in `each'
                                                                /usr/lib/ruby/vendor_ruby/rubygems/request_set.rb:183:in `install'
                                                        /usr/lib/ruby/vendor_ruby/rubygems/commands/install_command.rb:215:in `install_gem'
                                                                /usr/lib/ruby/vendor_ruby/rubygems/commands/install_command.rb:231:in `block in install_gems'
        /usr/lib/ruby/vendor_ruby/rubygems/commands/install_command.rb:224:in `each'
        /usr/lib/ruby/vendor_ruby/rubygems/commands/install_command.rb:224:in `install_gems'
                /usr/lib/ruby/vendor_ruby/rubygems/commands/install_command.rb:170:in `execute'
                        /usr/lib/ruby/vendor_ruby/rubygems/command.rb:328:in `invoke_with_build_args'
                                /usr/lib/ruby/vendor_ruby/rubygems/command_manager.rb:253:in `invoke_command'
                                        /usr/lib/ruby/vendor_ruby/rubygems/command_manager.rb:193:in `process_args'
                                        /usr/lib/ruby/vendor_ruby/rubygems/command_manager.rb:151:in `run'
                                /usr/lib/ruby/vendor_ruby/rubygems/gem_runner.rb:52:in `run'
                /usr/bin/gem:12:in `<main>'
                                                                                                                        
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ (umask 0077 && echo ${GIST_TOKEN(umask 0077 && echo ${GIST_TOKEN} > ~/.gist)                                 
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ export LAB_NUMBER=01
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ git clone https://github.com/tp-labs/lab${LAB_NUMBER} tasks/lab${LAB_NUMBER}
Cloning into 'tasks/lab01'...
                             remote: Enumerating objects: 74, done.
                                                                   remote: Coremote: Counting objects: 100% (3/3), done.
                                           remote: Compressing objects:  33% remote: Compressing objects: 100% (3/3), done.
remote: Total 74 (delta 0), reused 1 (delta 0), pack-reused 71 (from 1)
                                                                       ReceivReceiving objects: 100% (74/74), 945.07 KiB | 2.65 MiB/s, done.
                                                               Resolving deltResolving deltas: 100% (20/20), done.
                                                                                                                  
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ mkdir reports/lab${LAB_NUMBER}
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ cp tasks/lab${LAB_NUMBER}/READMEcp tasks/lab${LAB_NUMBER}/README.md reports/lab${LAB_NUMBER}/REPORT.md
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace]
                                         └─$ cd reports/lab${LAB_NUMBER}
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace/reports/lab01]
                                                       └─$ edit REPORT.md
                                                                             
┌──(kali㉿kali)-[~/mrglist3431/workspace/reports/lab01]
    
                                                                             
──(kali㉿kali)-[~/boost-libs]
└─$ history
    1  gist REPORT.md
    2  $ wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
    3  wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
    4  tar -xf boost_1_69_0.tar.gz -C ~
    5  cd ~/boost_1_69_0
    6  find -maxdepth 1 ! -type d  | wc
    7  find ! -type d | wc
    8  find ! -type d -name "*.h" | wc
    9  find ! -type d -name "*.cpp" | wc
   10  find ! -type d ! -name "*.cpp" ! -name "*.h" | wc
   11  find -name "any.hpp"
   12  grep -lr "boost::asio"
   13  sudo apt install libicu-dev
   14  ./bootstrap.sh
   15  sudo ./b2 install
   16  mkdir ~/boost-libs
   17  cp `find -name "*.a"` ~/boost-libs
   18  cd ~/boost-libs
   19  find ! -type d -exec du -h {} +
   20  find ! -type d -exec du {} + | sort -rn | head -n 10
                                                                             
┌──(kali㉿kali)-[~/boost-libs]
└─$ 

    
                                                                             

