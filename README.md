# kafka-sandbox-ansible

This is a simple ansible project that can be used in order to create a kafka sandbox, for development purpose or some tests.

It can run under fedora or rhel server (or vm, or whatever is on this two os)

I just needed it so I used ansible scripts given by confluent, changed some things so as to optimize it them for a single node environnement.

# How to use ?

1. Install Python on the server (yum install python)
4. Change the server-ip in the host.yml
5. Launch the ansible script <=> ansible-playbook -i host.yml single_kafka_dev_env.yml

You're done.