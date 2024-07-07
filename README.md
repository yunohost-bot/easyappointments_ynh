<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Easy!Appointments for YunoHost

[![Integration level](https://dash.yunohost.org/integration/easyappointments.svg)](https://ci-apps.yunohost.org/ci/apps/easyappointments/) ![Working status](https://ci-apps.yunohost.org/ci/badges/easyappointments.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/easyappointments.maintain.svg)

[![Install Easy!Appointments with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=easyappointments)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Easy!Appointments quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Easy!Appointments is a highly customizable web application that allows customers to book appointments with you via a sophisticated web interface. Moreover, it provides the ability to sync your data with Google Calendar so you can use them with other services. It is an open source project that you can download and install even for commercial use. Easy!Appointments will run smoothly with your existing website as it can be installed in a single folder of the server and of course share an existing database.

### Features
The application is designed to be flexible enough so that it can handle any enterprise work flow.

- Customers and appointments management.
- Services and providers organization.
- Working plan and booking rules.
- Google Calendar synchronization.
- Email notifications system.
- Self hosted installation.
- Translated user interface.


**Shipped version:** 1.5.0~ynh1

**Demo:** <https://demo.easyappointments.org/>

## Screenshots

![Screenshot of Easy!Appointments](./doc/screenshots/screenshots.png)

## Documentation and resources

- Official app website: <https://easyappointments.org/>
- Official admin documentation: <https://easyappointments.org/docs.html#1.4.3/readme.md>
- Upstream app code repository: <https://github.com/alextselegidis/easyappointments>
- YunoHost Store: <https://apps.yunohost.org/app/easyappointments>
- Report a bug: <https://github.com/YunoHost-Apps/easyappointments_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
or
sudo yunohost app upgrade easyappointments -u https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
