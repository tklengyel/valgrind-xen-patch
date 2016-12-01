# valgrind-xen-patch
Patch to Valgrind 3.12 to bring it up-to-date with Xen 4.8

 - wget http://valgrind.org/downloads/valgrind-3.12.0.tar.bz2
 - tar xvf valgrind-3.12.0.tar.bz2
 - cd valgrind-3.12.0
 - patch -p0 < ../valgrind-xen48.patch
 - ./configure
 - make
 - make install
