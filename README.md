# docker-ssh-server
 
Build OpenSSH Server in Docker Container

## Start
- Select your OS (Ubuntu, CentOS) and change the current folder
- run `./init.sh`
- run this command to connect your ssh server container
    ```bash
    # Default port is 11111
    ssh -p <port> <ID>@<IP Address>
    
    # Example: ssh -p 11111 root@<IP Address>
    ```