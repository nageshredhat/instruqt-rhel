---
slug: login
id: 2tzuyjsmcszl
type: challenge
title: Log into the Web Console
notes:
- type: text
  contents: |
    # Goal:
    After completing this scenario, users will be able to use the web console to monitor the performance of Red Hat Enterprise Linux 8 systems.

    # Concepts included in this scenario:
    * Authenticating to the **Web Console**
    * Inspect system performance using the **PCP-Cockpit** integration
tabs:
- title: Terminal
  type: terminal
  hostname: rhel
- title: RHEL Web Console
  type: external
  url: https://rhel.${_SANDBOX_ID}.instruqt.io:9090
difficulty: basic
timelimit: 3000
---
Click on the tab titled **RHEL Web Console** at the top of  your lab system interface. Selecting this tab will open the lab system's Web Console in a
new browser tab or window.

![web console](../assets/pop-out-2.png)

Click `Advanced`

![Connection not private](../assets/connection-not-private.png)

Then click `Proceed to rhel.xxxx.instruqt.io`

![Proceed](../assets/proceed.png)

Once the login page is presented, use the following credentials to log into the Web Console:

Username: **rhel**\
Password: **redhat**

![Web Console Login](../assets/Web-console-login.png)

Now that you are logged into the Web Console, we must turn on administrative access.

Click `Turn on administrative access`.

![admin access](../assets/turn-on-admin.png)

Next do the following:

1) Enter the password: **redhat**
2) Click `Authenticate`

![auth](../assets/auth.png)
