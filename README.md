# www.patricklin.ca

Source for patricklin.ca

## Digital Ocean 

Based on:

- [https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-16-04](https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-16-04)
- [https://www.digitalocean.com/community/tutorials/how-to-set-up-a-node-js-application-for-production-on-ubuntu-16-04](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-node-js-application-for-production-on-ubuntu-16-04)

### SSH into your droplet 


```
$ ssh root@your_droplet_ip
$ ssh plin@138.68.14.122
```

### Generate SSH Keys 

See [https://www.digitalocean.com/community/tutorials/how-to-use-ssh-keys-with-digitalocean-droplets](https://www.digitalocean.com/community/tutorials/how-to-use-ssh-keys-with-digitalocean-droplets)


## Nginx Web Server 

### Status 

```
$ systemctl status nginx
```

### Start | Stop | Restart | Reload


```
$ sudo systemctl [command] nginx
```