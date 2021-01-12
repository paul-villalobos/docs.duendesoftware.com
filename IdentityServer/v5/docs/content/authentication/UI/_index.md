+++
title = "Pages"
date = 2020-09-10T08:20:20+02:00
weight = 10
chapter = true
+++

# Pages

As browser requests are made to the protocol endpoints in your IdentityServer, they will be redirected to the interactive pages for the user to see. Depending on the features required, the pages expected in your IdentityServer are:
* [Login]({{< ref "./login" >}}): allows the user to login. This could be achieved with a local credential, or could utilize an external login provider (e.g. social or enterprise federation system).
* [Logout]({{< ref "./logout" >}}): allows the user to logout (including providing single sign-out).
* [Error]({{< ref "./error" >}}): display error information to the end user, typically when there are workflow errors.
* [Consent]({{< ref "./consent" >}}): allows the user to grant resource access to clients (typically only used if the client is third-party).

[Additional pages]({{< ref "./custom" >}}) that you might want are then also possible (e.g. password reset, registration), and those are typically available to the user as links from one of the above pages.
