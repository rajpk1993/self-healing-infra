# self-healing-infra
This solution can be used to explore auto-remediation, this is still being developed and new features can be added to improve the solution.
Main idea for the project is to reduce manual invervention, and automate remediation of events/alerts.

![Self_Updated](https://user-images.githubusercontent.com/64710536/127380823-3d3db870-b65f-4907-9e22-7d7c4e7c64a9.png)


Pre-requisites:

1) Google Cloud Account # GCP offers free credit to explore and learn.
2) Sensu # Monitoriong Tool.
3) Ansible Tower # AWX is the upstream project, I am using OKD Cluster to deploy AWX Tower.
4) Nginx Web-Server # To implement the and test the solution.

Future Scope:
1) Adding Hashicorp Vault to manage credentails, tokens and passwords.
2) Integrating with Slack and Grafana.
