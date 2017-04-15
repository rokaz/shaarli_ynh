shaarli_ynh - Shaarli app for Yunohost
===========
This app intends to provide to Yunohost'users Shaarli (https://github.com/shaarli/Shaarli), a simple but advanced bookmarking service.

It is based on the community version of Shaarli (from @sebsauvage original software).

Current version: **0.8.3**

**Warning**: Work In Progress - **not ready for daily use**. (see https://github.com/YunoHost-Apps/shaarli_ynh/tree/v0.0.41beta if you need a stable version).
Related topic on Yunohost's forum: https://forum.yunohost.org/t/fr-en-shaarli-app-lets-remove-the-dust/2200/

Help for dev/testing hightly appreciated :)

## Current features

    * Install / remove scripts
    * Backup/restore scripts
    * Adding / removing a link
    * Upgrade *not tested*
    * Configure Shaarli during installation

## Installation information

When doing the installation you will be prompted if you want to have a public site, meaning that you don't have to be a user of this Yunohost instance to access the site.

You will also be asked if you want to   have a private instance, meaning that the authentication will be deactivated and the application will be only available to the owner designed during install.

## TODO
    
    * Integrate the ssowat authentication (currently the authentication is done by Shaarli)
    * Test more the package

## Changelog

For Shaarli changelog, see: https://github.com/shaarli/Shaarli/blob/master/CHANGELOG.md
