# plogonway

A [Dalamud](https://github.com/goatcorp/Dalamud) custom plugin repository for the plugins ("plogons") made by **notingway**.

> **These are third-party, experimental plugins.** They are not reviewed by the Dalamud team, which offers only minimal support for plugins from custom repositories. Use them at your own risk, and report problems to the plugin's own repository, not to Dalamud.

## How to add it

1. In game, open `/xlsettings` and go to the **Experimental** tab.
2. Under **Custom Plugin Repositories**, paste this address and add it:

   ```
   https://raw.githubusercontent.com/notingway/plogonway/main/plogonway.json
   ```

3. Save, then open `/xlplugins`. The plugins below appear under **All Plugins**.

## The plugins

| Plugin | What it does | Status |
| --- | --- | --- |
| [Duty Notes](https://github.com/notingway/duty-notes) | An in-game overlay for your notes on a duty: mechanics, the mitigation skills to use, and free text, switching by itself when you enter the duty. | Experimental, not released yet |

## For the author

`plogonway.json` is the repository file that Dalamud reads: one array, one entry per plugin. The entries are written by each plugin's release script (see `docs/RELEASING.md` in the plugin's repository), from the manifest the build generates, so they are not edited by hand. Once users have added the address above, **the file name and the repository name must never change**.

## License

[MIT](LICENSE), copyright notingway.