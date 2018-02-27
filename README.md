# Craft CP Zendesk plugin for Craft CMS

Enable Zendesk for logged in users in the Control Panel

## Installation

To install Craft CP Zendesk, follow these steps:

1. Download & unzip the file and place the `craftcpzendesk` directory into your `craft/plugins` directory
2.  -OR- do a `git clone https://github.com/kmelve/craftcpzendesk.git` directly into your `craft/plugins` folder.  You can then update it with `git pull`
3.  -OR- install with Composer via `composer require netliferesearch/craftcpzendesk`
4. Install plugin in the Craft Control Panel under Settings > Plugins
5. The plugin folder should be named `craftcpzendesk` for Craft to see it.  GitHub recently started appending `-master` (the branch name) to the name of the folder for zip file downloads.

Craft CP Zendesk works on Craft 2.4.x and Craft 2.5.x.

## Craft CP Zendesk Overview

This plugin enables the Zendesk widget in the Craft Control Panel. This is handy if you want to offer support if you are responsible for
clients Craft websites

## Configuring Craft CP Zendesk

The plugin needs the Zendesk App ID in order to work.

`https://app.zendesk.io/a/apps/XXXXXXXX/`

You can also add the Secret Key that Zendesk uses for [secure mode](). You'll find it your Zendesk App Settings under _secure mode_. This is recommended, but [read the documentation](https://docs.zendesk.com/configure-zendesk-for-your-product-or-site/staying-secure/enable-secure-mode-on-your-web-product) and make sure you understand the implications.

If you want to be able to segment on company, you can add an identifier for this as well. The company name is usually the way to go.

## Using Craft CP Zendesk

Once you have set it up with the Zendesk App ID, the widget will appear on the site _for all logged in users_.

## Craft CP Zendesk Roadmap

* Choose or create companies in the Control Panel
* Make it available for only certain users/groups
* ~~Release it~~

## Craft CP Zendesk Changelog

### 1.0.0 -- 27.02.2018

* Initial release

Brought to you by [Netlife Research](https://github.com/netliferesearch)
