---
title: "Security & Compliance Center PowerShell"
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 9/29/2015
ms.audience: Admin
ms.topic: article
ms.service: exchange-powershell
localization_priority: Normal
ms.assetid: 2f33bb84-cede-46f6-9d39-d246e8ce3543
search.appverid: MET150
description: "Learn about using Security & Compliance Center PowerShell."
---

# Security & Compliance Center PowerShell

Security & Compliance Center PowerShell is the administrative interface that enables you to manage the features that are available in the Security & Compliance Center from the command line. For example, you can use Security & Compliance Center PowerShell to perform Compliance Searches and configure access to the Security & Compliance Center. The following topics provide information about using Security & Compliance Center PowerShell:

- To create a remote PowerShell session that supports both modern authentication and multi-factor authentication (MFA), see [Connect to Security & Compliance Center PowerShell](connect-to-scc-powershell.md). Note that the connection instructions are different from Exchange Online PowerShell or standalone Exchange Online Protection (EOP) PowerShell (the _ConnectionUri_ value is different).

- To learn about the structure and layout of the cmdlet reference topics in Security & Compliance Center PowerShell, see [Exchange cmdlet syntax](exchange-cmdlet-syntax.md).

Many of the cmdlets that are available in Security & Compliance Center PowerShell correspond to features that are only available in the Security & Compliance Center, so the related cmdlets are exclusive to Security & Compliance Center PowerShell. But, some cmdlets that are available in Security & Compliance Center PowerShell have the same names and functionality as those in Exchange Online PowerShell (for example, [Get-User](https://docs.microsoft.com/powershell/module/exchange/get-user)).

Also, some features that are available in the Security & Compliance Center (for example, [anti-spam and anti-malware](https://docs.microsoft.com/microsoft-365/security/office-365-security/anti-spam-and-anti-malware-protection) cmdlets are only available in [Exchange Online PowerShell](exchange-online-powershell.md)). Check the **Applies to** value in the cmdlet reference topic to verify where the cmdlet actually resides.
