docker-engine
=========

This role installs and manages docker engine on Ubuntu >= 14.04

Requirements
------------

None

Role Variables
--------------

apt_cache_valid_time: 3600

python_update_repo: ppa:fkrull/deadsnakes-python2.7

docker_gpg_key_id: 9DC858229FC7DD38854AE2D88D81803C0EBFCD88

docker_gpg_key_url: https://download.docker.com/linux/ubuntu/gpg

docker_apt_repo: "deb [arch=amd64] https://download.docker.com/linux/ubuntu trusty stable"

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: docker-engine }

License
-------

Apache 2.0

Author Information
------------------

Reuben Stump 
<reuben.stump@gmail.com>
