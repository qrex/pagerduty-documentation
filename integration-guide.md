# PagerDuty + unitQ Monitor Integration Benefits

* Notify your team in PagerDuty when new customer feedback data arrives, when existing Quality Monitors start to trend and when new Quality Monitors are detected.
* unitQ Monitor can trigger, acknowledge, and resolve incidents on the PagerDuty services you integrate.

# How It Works

* When an alert triggers in the unitQ Monitor, it sends a notification to the specified PagerDuty services and creates a PagerDuty incident. Any users subscribed to that service can receive the notification and act upon it.
* If you selected **Send recovery notification** when you configured the alert in the unitQ Monitor, when the alert condition returns to the recovery threshold, unitQ Monitor sends out another notification to PagerDuty.

# Requirements

* To integrate with PagerDuty, your PagerDuty account must have the [admin user role](https://support.pagerduty.com/docs/user-roles) to add the app. If you do not have the admin role, contact your IT team to configure your account correctly.

# Support

If you need help with this integration, please contact [hello@unitq.com](mailto:hello@unitq.com).

# Integration Walkthrough
## In PagerDuty

There are no integration steps on the PagerDuty side, other than configuring any new PagerDuty services that you want to integrate with unitQ.

## In unitQ Monitor

In the unitQ Monitor, you first need to install the PagerDuty app. Then you can configure unitQ Monitor alerts to send notifications to your PagerDuty services.

## Install the PagerDuty App

1. In the unitQ Monitor, click **Integrations** in the left-hand menu.
1. Under the PagerDuty logo, click **Available**.
1. In the dialog that appears, click **Add Channel**.
1. Your browser redirects to PagerDuty. Log in to PagerDuty with your PagerDuty account credentials. 
1. In the **Select Services** list, select the service or services you want to integrate with unitQ Monitor, then click **Connect**.
1. Your browser redirects to the unitQ Monitor Integrations page. Click **Close**.

## Add PagerDuty to a unitQ Alert

You can have unitQ Monitor automatically open a PagerDuty incident when a unitQ alert triggers. Anyone within your organization who has access to both unitQ Monitor and PagerDuty can create new PagerDuty channels or edit existing channels.

1. In the unitQ Monitor, click **Alerts** in the left-hand menu.
1. To create a new alert, click **Create Alert**.
   To edit an existing alert, select the alert, click the hamburger icon (&#9776;), then click **Edit**.
1. Select the alert method, definition, and condition. To learn about creating an alert, read [Create Alerts](https://unitq.zendesk.com/hc/en-us/articles/360053232614-Create-Alerts).
1. Click the **Notify Team** dropdown, then do one of the following:
   1. To select an existing PagerDuty service, select it in the dropdown.
   1. To choose a different PagerDuty service, select **Add New PagerDuty Channel**. This opens the PagerDuty login page.
      1. Your browser redirects to PagerDuty. Log in to PagerDuty with your PagerDuty account credentials. 
      1. In the **Select Services** list, select the service or services you want to integrate with unitQ Monitor, then click **Connect**.
      1. Your browser redirects to the unitQ alert creation page.
1. Click **Save** at the bottom of the page to complete your PagerDuty integration. 

# How to Uninstall

1. In PagerDuty, choose **Services** > **Service Directory**, select the unitQ Monitor service.
1. Click **Integrations** tab.
1. Click the gear icon, then click **Delete Integration**. Click **OK** to confirm.
