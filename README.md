## TenantCloud Angular Testing Postfix Templates for PhpStorm ##

How to:

1) Install *Custom Postfix Templates* plugin *Preferences | Plugins*

2) Clone this repo to your local machine https://github.com/tenantcloud/angular-postfix-templates.git

3) Click on the "+" sign and choose Javascript from the dropdown

4) Add local path in *Preferences | Editor | Custom Postfix Templates*:
    * Type: **Local file in your system**
    * URL: **\<path to your cloned project\>/spectator.postfixTemplates**
    * Local filename: **Spectator**


## Supported Live Templates ##

- [Spectator Inject](#spectator-inject)

### Spectator Inject ###

```
// store.sin + Tab
store = spectator.inject(Store);
```
