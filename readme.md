
Данный репозитарий это адаптация патча файловой системы aufs версии 4 

*-------------------------------------------*

  Aufs4 -- advanced multi layered unification filesystem version 4.x
  
  http://aufs.sf.net
  
  Junjiro R. Okajima

*-------------------------------------------*

для ядра линукс версии 5.7.1


patch -Np1 -i ../aufs5-patch/aufs5-base.patch

patch -Np1 -i ../aufs5-patch/aufs5-kbuild.patch

patch -Np1 -i ../aufs5-patch/aufs5-mmap.patch

