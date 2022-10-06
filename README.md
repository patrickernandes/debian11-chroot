# Instalando Debian 11 em ambiente chroot

Script em Shell para instalação Debian 11 (pt-br) em ambiente chroot.

Alguns pontos a observar:

É necessário configurar algumas variáveis dentro do script antes de iniciar.  

Também temos que exportar a variável 'disk' informando qual o disco de instalação:

```
export disk='/dev/sda'
```

A partição de instalação deve ser montada na pasta "/mnt".  

Agora, só executar:

```
sh install | tee -a log.txt
```

O processo de instalação será iniciado e os logs armazenados no arquivo 'log.txt', que pode ser visualizado posteriormente.

Espero ter ajudado.. ;)