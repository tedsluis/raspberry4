# Letsencrypt swag

## documentation

* https://github.com/linuxserver/docker-swag
* https://hub.docker.com/r/linuxserver/swag

## dependecies

* duckdns account, domain and token [https://www.duckdns.org](https://www.duckdns.org/faqs.jsp)
* host belongs to inventory group *letsencrypt* with *inventory/group_vars/letsencrypt.yml*

## vars 

| var                    | source                           | description                             |
|------------------------|----------------------------------|-----------------------------------------|
| _duckdns_token         | inventory/group_vars/vault.yaml  | your duckdn token                       |
| _letsencrypt_domain    | inventory/group_vars/letsencrypt | your domain                             |
| _letsencrypt_image_tag | inventory/group_vars/letsencrypt | docker image tag linuxserver/swag:<tag> |
| _letsencrypt_staging   | inventory/group_vars/letsencrypt | true = testing                          |
| _letsencrypt_users     | inventory/group_vars/letsencrypt | uid/gid used to run container           |
| _mail_address          | inventory/group_vars/all         | your mail address                       |
| _timezone              | inventory/group_vars/all         | your timezone                           |

