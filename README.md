# Service deployment

## Services

* GitLab-CE
* GitLab Runner
* Mail admin
* Mail client
* Mail server

### Problemas

#### Correo en bucle
Limpiar la cola de envio y purgar el buzón de entrada
```
postsuper -d ALL
doveadm expunge -u email@redmic.es mailbox INBOX ALL
```
