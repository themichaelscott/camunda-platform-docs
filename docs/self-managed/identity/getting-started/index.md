---
id: index
title: "Installation and first steps"
sidebar_label: "Installation and first steps"
---

## Installation

To use Identity, first install it locally via Docker or Kubernetes.

Follow the [Installation Guide](/docs/self-managed/platform-deployment/).

## Accessing the UI

As soon as the component is started, you can access the login page and log in to the Identity application.

Navigate to [localhost:8080](http://localhost:8080) to see the UI exposed by the Identity component.

![identity-login-page](./img/identity-login-page.png)

## Default user

The configuration in this guide creates an example user during installation; use this account to log in.

```text
Username: demo
Password: demo
```

:::note Want to create more users?
Creating a user in Identity is not currently supported. To create a user, see
[Keycloak's documentation on creating a user](https://www.keycloak.org/docs/latest/server_admin/#proc-creating-user_server_administration_guide).
:::

## Home screen

You are directed to the home page once logged in successfully.

![identity-landing-page](./img/identity-landing-page.png)