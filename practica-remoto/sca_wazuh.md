### Corrección de errores gracias al escaner SCA

## Asegurate de que Telnet esta desinstalada


![alt text](image.png)

- El comando que necesitamos para asegurarnos de este proceso es:
```
apt purge telnet
```

![alt text](image-1.png)

## Asegurate de que auditd esta instalado



![alt text](image-2.png)

- El comando que necesitamos para asegurarnos de este proceso es:
```
 apt install auditd audispd-plugins
```

![alt text](image-3.png)

## Asegurate de que nftables esta instalado

![alt text](image-4.png)


- El comando que necesitamos para asegurarnos de este proceso es:
```
 apt install nftables
```

![alt text](image-5.png)

En el SCA dice que ese paso estaba failed pero se equivoca, ya que si que estaba instalado

## Asegurate de que este systemd-journal-remote instalado

![alt text](image-6.png)

- El comando que necesitamos para asegurarnos de este proceso es:
```
 apt install systemd-journal-remote
```

![alt text](image-7.png)
