# VSCodeServer

![stack Overflow](https://sincrack.com/vscode.jpg)

    volumes:
      - /volume1/docker/VSCode/config:/config
      - /volume1/docker:/volume1/docker
      - /var/run/docker.sock:/var/run/docker.sock

Editar los volumenes que quieras montar, para usar la extension de docker es necesario montar el sock, sino vas a hacer uso de ella no es necesario.


Fichero docker-compose.yml preparado para configurar VSCode de forma sencilla.
Pensado para configurar detras de un proxy con SSL por ejemplo Nginx Proxy Manager.
