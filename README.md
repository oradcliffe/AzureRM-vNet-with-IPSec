# AzureRM-vNet-with-IPSec

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Foradcliffe%2FAzureRM-vNet-with-IPSec%2Fmaster%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Foradcliffe%2FAzureRM-vNet-with-IPSec%2Fmaster%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a>

This template deploys a **vNet with three subnets, a gateway subnet, and a local and virtual network gateway, along with a connection for site-to-site IPsec VPN**.

`Tags: vNet, VPN, site-to-site`

## Solution overview and deployed resources

This solution deploys a vNet with three subnets, a gateway subnet, and a local and virtual network gateway, along with a connection for IPsec VPN.

#### Resources

This template deploys a vNet, local network gateway, virtual network gateway, public IP for the virtual network gateway, and a connection.

## Prerequisites

There are no prerequisites

## Deployment steps

You can click the "deploy to Azure" button at the beginning of this document.

## Notes
When you deploy, it is easiest to use a new resource group.  Verify that your local gateway IP is filled out - this will be the public IP you are connecting to Azure and is most likely not the default of 1.1.1.1.  Local address prefix will be the CIDR block that you want communicating with the virtual network.  Deployment takes roughly 45 minutes on average.


