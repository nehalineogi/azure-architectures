# azure-architectures

Visio Diagrams for Azure Architectures based on Partner ADS sessions


## WVD Architectures

1) Two AD Forests, On-Prem AD Sync to Azure, Hybrid Design with VPN
![WVD HLD](images/WVD-two-forest-hybrid-with-VPN-to-Azure.jpg)
2) Two AD Forests, On-Prem AD Sync to Azure, AAD DS (Managed Instance) without VPN
![WVD HLD](images/WVD-two-forest-AADDS-without-VPN-to-Azure.jpg)
3) Two AD Forests, On-Prem AD Sync to Azure, AAD DS (Managed Instance) with VPN
![WVD HLD](images/WVD-two-forest-hybrid-with-VPN-to-Azure-AADDS-POC.jpg)

## Virtual WAN Architectures

- Terraform LAB
- With P2S, S2S and ER

![VWAN HLD](images/vWAN-terraform.JPG)

## NVA Architectures

1) On Premises to Azure East-West using LB HA Ports
![On Premises to Azure East-West](images/nva/on-prem-to-azure-east-west-lb-ha-ports.JPG)
2) Spoke to Spoke East-West using LB HA Ports
![Spoke to Spoke East-West](images/nva/spoke-to-spoke-east-west-lb-ha-ports.JPG)
3) North South traffic using LB Sandwich design
![North South](images/nva/north-south-lb-sandwich-design.JPG)