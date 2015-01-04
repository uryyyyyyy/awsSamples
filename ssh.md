


# mount
sshfs guestuser@XXX.XXX.XXX.XXX:/path/to/gest/folder/ /path/to/host/folder/

sshfs -o IdentityFile=/path/to/amazon_key.pem ec2-user@XXX.XXX.XXX.XXX:/home/ec2-user/share/ ~/share

# unmount
fusermount -u ~/share/
