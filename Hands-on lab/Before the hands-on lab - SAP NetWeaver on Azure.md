
![](https://github.com/Microsoft/MCW-Template-Cloud-Workshop/raw/master/Media/ms-cloud-workshop.png "Microsoft Cloud Workshops")

<div class="MCWHeader1">
SAP NetWeaver on Azure
</div>

<div class="MCWHeader2">
Before the hands-on lab setup guide
</div>

<div class="MCWHeader3">
October 2018
</div>


Information in this document, including URL and other Internet Web site references, is subject to change without notice. Unless otherwise noted, the example companies, organizations, products, domain names, e-mail addresses, logos, people, places, and events depicted herein are fictitious, and no association with any real company, organization, product, domain name, e-mail address, logo, person, place or event is intended or should be inferred. Complying with all applicable copyright laws is the responsibility of the user. Without limiting the rights under copyright, no part of this document may be reproduced, stored in or introduced into a retrieval system, or transmitted in any form or by any means (electronic, mechanical, photocopying, recording, or otherwise), or for any purpose, without the express written permission of Microsoft Corporation.

Microsoft may have patents, patent applications, trademarks, copyrights, or other intellectual property rights covering subject matter in this document. Except as expressly provided in any written license agreement from Microsoft, the furnishing of this document does not give you any license to these patents, trademarks, copyrights, or other intellectual property.

The names of manufacturers, products, or URLs are provided for informational purposes only and Microsoft makes no representations and warranties, either expressed, implied, or statutory, regarding these manufacturers or the use of the products with any Microsoft technologies. The inclusion of a manufacturer or product does not imply endorsement of Microsoft of the manufacturer or product. Links may be provided to third party sites. Such sites are not under the control of Microsoft and Microsoft is not responsible for the contents of any linked site or any link contained in a linked site, or any changes or updates to such sites. Microsoft is not responsible for webcasting or any other form of transmission received from any linked site. Microsoft is providing these links to you only as a convenience, and the inclusion of any link does not imply endorsement of Microsoft of the site or the products contained therein.

© 2018 Microsoft Corporation. All rights reserved.

Microsoft and the trademarks listed at <https://www.microsoft.com/en-us/legal/intellectualproperty/Trademarks/Usage/General.aspx> are trademarks of the Microsoft group of companies. All other trademarks are property of their respective owners.

**Contents**

<!-- TOC -->

- [SAP NetWeaver on Azure before the hands-on lab setup guide](#\sap-netweaver-on-azure-before-the-hands-on-lab-setup-guide)
    - [Requirements](#requirements)
    - [Before the hands-on lab](#before-the-hands-on-lab)
        - [Task 1: Review the relevant Microsoft documentation](#task-1-review-the-relevant-microsoft-documentation)

<!-- /TOC -->

# SAP NetWeaver on Azure before the hands-on lab setup guide

## Requirements

-   A Microsoft Azure subscription with at least 36 vCPU available in the Azure region where the lab Azure VMs will reside.

    -   DC VMs -- 2 x DS2\_v2: 2 x 2 vCPUs = 4 vCPUs

    -   S2D VMs -- 2 x DS3\_v2: 2 x 4 vCPUs = 8 vCPUs

    -   ASCS VMs -- 2 x DS2\_v2: 2 x 2 vCPUs = 4 vCPUs

    -   DB VMs -- 2 x DS4\_v2: 2 x 8 vCPUs = 16 vCPUs

    -   APP VMs -- 2 x DS2\_v2: 2 x 2 vCPUs = 4 vCPUs

-   A lab computer running Windows 7 or newer and configured with:

    -   Azure PowerShell (AzureRM module version 5.7.0 or newer)

-   Access to SAP Software Provisioning Manager (SWPM) version SPS24 or newer (requires an SAP Online Service System account)

-   Access to NTCLUST.SAR including the current SAP cluster resource DLL (requires an SAP Online Service System account)

-   Access to Internet from the lab VMs

## Before the hands-on lab

Timeframe: 30 minutes

Review the relevant Microsoft documentation.

### Task 1: Review the relevant Microsoft documentation 

1.  Review to the documentation regarding highly available architecture and scenarios of SAP NetWeaver on Azure at <https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/sap/sap-high-availability-architecture-scenarios>.

2.  Review to the documentation regarding Azure PowerShell at <https://docs.microsoft.com/en-us/powershell/azure/get-started-azureps?view=azurermps-6.10.0>.

You should follow all steps provided *before* attending the hands-on lab.
