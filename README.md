# `ETCD UI Service`

* Open your browser and enter the address: http://127.0.0.1:7070/etcdkeeper
* Click on the version of the title to select the version of ETCD. The default is V3. Reopening will remember your choice.
* Right click on the tree node to add or delete.
* For secure mode, authentication is required. User name and password needs to be entered in the dialogue box.
* Username is 'root' and default password is located at ETCD_ROOT_PASSWORD key under environment section in [docker_setup/provision/dep/docker-compose-provision.override.prod.yml](../docker_setup/provision/dep/docker-compose-provision.override.prod.yml).
> **NOTE** if ETCD_ROOT_PASSWORD is changed, EIS must to be provisioned again.
