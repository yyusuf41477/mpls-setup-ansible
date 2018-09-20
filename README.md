# mpls-setup-ansible
MPLS INFRASTRUCTURE USING ANSIBLE



This lab demonstrates the deployment of an entire end to end MPLS network using Ansible. The lab starts off by running a playbook to setup the base infrastructure after having ospf enabled

it sets up cef and ldp for mpls to be up and ready for mp-bgp

it then sets up bgp to the participating PEs with hard coded variable.later in the next factoring we shall setup the variables into a templating engine then invoke a role to call the setup hitlessly

This lab was inpsired by David Bombal, who has some fantastic Ansible and other automation guides outlining various deployment and configuration scenarios and resources. Many thanks to David, we need more sharing in the network automation space!!!

