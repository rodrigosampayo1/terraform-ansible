# terraform-ansible
## Ansible
- agentless (Chef and Puppet have/need agents)
- configuration managment and infrastructure deployment for hybrid clouds
- Configuration managment within Ansible
- Ansible playbooks are written in YAML
- Ansible is not stateful -> dont keep track. Thefore, In every run, Ansible compare against the current state with the template.
- Ansible is Prodecural-playbook- and declarative modules -aws-
- OS agnostic -> because it offers a vast array of modules for every OS-level utility as well as cloud and on-prem infra vendors

## Terraform
- Cloud agnostic -> work for every cloud -> multiprovider
- infrastructure provisioning
- Stateful -> keep track of state of infra deployment, local o remote state files.
- Type -> Declarative, HCL en JSON, vos pedis que queres, pero no pones como
- agentless, only need a host with a terraform binary on it
- Offers built in functions and conditionals
- Works for On-prem infra vendrois

## AWS Cloudformation
- Only AWS resources. It can be very granular.
- Cloudformation uses JSON or YAML
- Stateful -> keep track, but users dont need to worry
- type -> Declarative, Json or YAML
- agentless, it lives in AWS cloud.
- Offers built in functions and cross organizations deployments


## Differences:


