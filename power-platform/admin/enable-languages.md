---
title: "Regional and language options for your environment  | MicrosoftDocs"
description: Set regional and language options for your environment 
ms.custom: ""
ms.date: 08/19/2019
ms.reviewer: ""
ms.service: power-platform
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "get-started-article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
ms.assetid: 83200632-a36b-4401-ba41-952e5b43f939
caps.latest.revision: 31
author: "jimholtz"
ms.author: "jimholtz"
manager: "kvivek"
search.audienceType: 
  - admin
search.app: 
  - Powerplatform
---
# Regional and language options for your environment 

Enable languages in your organization to display the user interface and Help in a language that’s different from the base language. 

The following table shows tasks that are associated with changing regional and language options for your organization.  

|Task |  Description   |
|--------|---------|
|  **Set the base language**  |  The base language determines default settings for regional and language options in [!INCLUDE [pn-crm-shortest](../includes/pn-crm-shortest.md)] apps. After the base language is set, you can’t change it. |
| **Enable or disable languages** | You can enable or disable available languages in the **Settings** area. |
|  **Add and remove currencies**  | Similar to setting the base language, you select your organization's base currency during the purchasing process for a subscription to [!INCLUDE [pn-crm-shortest](../includes/pn-crm-shortest.md)] apps. After the base currency is set, you can’t change it.<br /><br /> However, if your organization uses more than one currency to track financial transactions, you can add currencies. |
| **Deactivate or activate currency records** |   You can’t delete currency records that are being used by other records, such as opportunities or invoices. However, you can deactivate currency records so they won’t be available for future transactions. |

## Enable the language  

These settings can be found in the Power Platform Admin center by going to **Environments** > [select an environment] > **Settings** > **Product** > **Languages**.

Make sure you have the System Administrator or System Customizer security role or equivalent permissions to update the setting.

- Follow the steps in [View your user profile](https://docs.microsoft.com/dynamics365/customer-engagement/basics/view-your-user-profile).
- Don’t have the correct permissions? Contact your system administrator.

 Before users can start using a Language Pack to display a language, the Language Pack must be enabled in your [!INCLUDE[pn_microsoftcrm](../includes/pn-dynamics-crm.md)] apps organization.  

1. Sign in to the Power Platform Admin center. 

2. Select an environment and go to **Settings** > **Product** > **Languages**.

   Here you’ll see each Language Pack installed in your environment, with a check box to the left of each listed Language Pack.  

4. For each Language Pack that you want to provision (enable), select the check box next to it. For each Language Pack that you want to unprovision (disable), clear the check box.  

5. Select **Apply**.  

6. Select **OK** on any confirmation dialog boxes that open.  

   > [!NOTE]
   >  It may take several minutes to provision or unprovision the languages.  

7. Select **Close** to close the **Language Settings** dialog box.

## Select the language to display the user interface and Help  

 Each user selects the language to display in an app.  See [Languages tab options](https://docs.microsoft.com/dynamics365/customer-engagement/basics/set-personal-options#languages-tab-options).

