---
title: App Center Diagnostics quickstart
author: mawillia
description: Get valuable diagnostic data in PlayFab with this App Center integration quickstart
ms.author: Marco.Williams
ms.date: 03/08/2019
ms.topic: article
ms.prod: playfab
ROBOTS: NOINDEX,NOFOLLOW
keywords: playfab, diagnostics, App Center, Crash Reporting, Crash Data, quickstart
ms.localizationpriority: medium
---

# Diagnostics with App Center quickstart (Private Preview)

> [!IMPORTANT]
> This feature is currently in **Private Preview**.  
>
> It is provided to give you an early look at an upcoming feature, and to allow you to provide feedback while it is still in development.  
>
> Access to this feature is restricted to select titles. If you are interested in trying it, please contact us at [helloplayfab@microsoft.com](mailto:helloplayfab@microsoft.com).

PlayFab is consistently looking to bring new capabilities to our game developers. We know how important it is to understand the health of your game as part of your overall LiveOps view. We are excited to announce that we have partnered with App Center to bring their diagnostic capabilities directly into PlayFab.

App Center provides tools to help you build, test, deploy and monitor mobile and PC apps. It is especially good at detecting when your app has crashed, and saving that information to help you fix it quickly.

## Prerequisites

You will need:

- A PlayFab Account.

- An App Center Account.

- The App Center SDK installed in your game.

- Private Preview enabled for your title (email [helloplayfab@microsoft.com](mailto:helloplayfab@microsoft.com)) to get access for your title.

## Getting started

To get started, log into your PlayFab account. Once App Center integration is enabled for your title (private preview only), you will see a **Diagnostics** tab in the sidebar.

![diagnostics tab screenshot image](media/diag_tab_screenshot.png)

Since the add-on has not yet been enabled, you will need to navigate to the add-ons page to turn on the integration.

- In **App Center Diagnostics**, select **Manage Add-Ons**.

![App Center Diagnostics - Manage Add Ons](media/go_to_addons_diag_page.png)

Select the install button on the **App Center Add-On** page. You should see the screenshot shown below.

![App Center Diagnostics - Add On Installed](media/addon-installed.png)

Now you need to link your PlayFab title to your App Center titles.

- To do this, select **Go to App Center**.

- You will be asked to authenticate for AppCenter, and will be provided with a list of titles you can select and link to your PlayFab title.
- If you have more iOS and Android App Center titles, be sure to select *both of them* to get your diagnostic information for both titles.

- Once you have completed the above steps, select the **Save Settings** button.

Your integration is now enabled. If you navigate back to the **Diagnostics** tab, you should see your crash data enabled.

![Diagnostics Tab Dashboard active Image](media/appcenter_gm_dash.png)
