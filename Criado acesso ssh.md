Habilitado o segundo adaptador de rede no modo "host only" (192.168.56.105)
````
$ sudo service sshd start
$ chkconfig sshd on
$ systemctl enable sshd.service
````
Inserido dns no windows (máquina física):
       - windows / system32/drivers/etc/hosts
```
192.168.56.105  redismysqllabcontainer
```
