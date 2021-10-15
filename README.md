# xrom4ik
<td>oot@50a455a6a059:/# $ pwd </td>

bash: $: command not found

root@50a455a6a059:/# ~ $ pwd

bash: /root: Is a directory

root@50a455a6a059:/# ~ $ cd /

bash: /root: Is a directory

root@50a455a6a059:/# $ ls

bash: $: command not found

root@50a455a6a059:/# / @ ls

bash: /: Is a directory

root@50a455a6a059:/# / $ ls -F --color

bash: /: Is a directory

root@50a455a6a059:/# ~ mkdir test

bash: /root: Is a directory

root@50a455a6a059:/# pwd

/
root@50a455a6a059:/# ls

1-t.txt  classic   error.txt  home        lib    libx32        ls-output.txt  newname  proc  sbin  tmp

bin      classics  etc        house       lib32  ls-error.log  media          nol      root  srv   usr

boot     dev       furniture  keldybaeva  lib64  ls-error.txt  mnt            opt      run   sys   var

root@50a455a6a059:/# ls -F --color test

oot@50a455a6a059:/# mkdir classics  

mkdir: cannot create directory 'classics': File exists

root@50a455a6a059:/# rndir classics

bash: rndir: command not found

root@50a455a6a059:/# rmdir classics

rmdir: failed to remove 'classics': Directory not empty

root@50a455a6a059:/# uname -s

Linux

root@50a455a6a059:/# uname -r

4.19.0-16-amd64

root@50a455a6a059:/# date

Fri Oct 15 12:55:44 UTC 2021
&

clear
root@50a455a6a059:~# ls

test

root@50a455a6a059:~# ls -R

.:
test

./test:

subtest

./test/subtest:

root@50a455a6a059:~#
/test/subtest:
root@50a455a6a059:~# ls type

ls: cannot access 'type': No such file or directory

root@50a455a6a059:~# type

root@50a455a6a059:~# type -F

bash: type: -F: invalid option

type: usage: type [-afptP] name [name ...]

root@50a455a6a059:~# /ets/X11

bash: /ets/X11: No such file or directory

root@50a455a6a059:~# mkdir ect

root@50a455a6a059:~# mkdir ect

mkdir: cannot create directory 'ect': File exists

root@50a455a6a059:~# cd ets

bash: cd: ets: No such file or directory

root@50a455a6a059:~# mkdri etc

bash: mkdri: command not found

root@50a455a6a059:~# cd etc

bash: cd: etc: No such file or directory



root@50a455a6a059:~# mkdir ets

root@50a455a6a059:~# mkdir etc

root@50a455a6a059:~# mkdir ect


mkdir: cannot create directory 'ect': File exists

root@50a455a6a059:~# cd  ect

root@50a455a6a059:~/ect# mkdir x11

root@50a455a6a059:~/ect# cd x11 

root@50a455a6a059:~/ect/x11# cd home

bash: cd: home: No such file or directory

root@50a455a6a059:~/ect/x11# cd ~

root@50a455a6a059:~# cd etc

root@50a455a6a059:~/etc# mkdir group

root@50a455a6a059:~/etc# mdir password

bash: mdir: command not found

root@50a455a6a059:~/etc# mkdie passwd

bash: mkdie: command not found

root@50a455a6a059:~/etc# mkdir passwd

root@50a455a6a059:~/etc# cat

root@50a455a6a059:~/etc# cat ets

cat: ets: No such file or directory

root@50a455a6a059:~/etc# touch group

root@50a455a6a059:~/etc# touc passwd

bash: touc: command not found

root@50a455a6a059:~/etc# touch passwd

root@50a455a6a059:~/etc# cat group


cat: group: Is a directory

root@50a455a6a059:~/etc# cat passwd

cat: passwd: Is a directory

root@50a455a6a059:~/etc# /test/subtest:

