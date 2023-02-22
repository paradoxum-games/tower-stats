<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD041 -->

<div align="center">
    <h1>🛠️ Tower Stats</h1>

    Automatically updated list of all tower stats
    along with a dedicated stat editor.
</div>

<hr />

## ⚙️ Usage

To edit existing stats, go to our [Stat Editor](https://paradoxum-games.github.io/tower-stats/) webpage.

## ✏️ Editing Stats

* Once you've arrived at the stat editor, you can select which tower you would like to edit stats for using the `Tower Selection` dropdown menu in the top right.
* Any stat that has a text input can be edited! This includes upgrade icons, titles, etc.

## 🎮 Testing Edited Stats

* Once you have edited a tower's stats to your liking, press the `Download Stats` button. This will download a [JSON](https://www.json.org/json-en.html) file of your edited stats.
* Once you have your edited stats downloaded, join the [Stat Editor Game](https://www.roblox.com/games/12508011272/Stat-Editor) and enter a match.
* Once in a match, open the console *(~ key for PC, /cmdr in chat for mobile)* and type the following: `set_stats ""`. Copy the JSON file you downloaded between the quotes and press `Enter`. If successful you should see `Overriden stats for specified towers.` in the console output.
* Running the stats command with different towers will accumulate changes, this means that you can run `set_stats` once with Soldier stats, and again with Scout stats.

## 📘 Saving And Loading

* Once you have edited stats of multiple towers of your liking, you can save all combined stats by using the `save_stats` command. This command requires you pass a name that you will later use to load stats from, so be sure to remember what you called your saves!
* When you want to load previously saved stats, you can use the `load_stats` command with the same name you saved the stats to.
* If you wish to export all stats combined, you can use the `export_stats` command. This will open a text box with your exported stats that you can copy paste from. It's highly recommended you export from this menu before sharing combined stats in the discord.

## ⚠️ Gotchas And Warnings

* Only one player's tower stat overrides will apply at a single time, if you apply a secondary stat change to a tower, it will override the previous changes!
* When changing the price of an upgrade, ensure that the next upgrade is more expensive. The game will sort upgrades by price and upgrades might get out of sync!
* When a tower is reworked in the future, there is a chance that your saved stats might become invalid! For this reason it is recommended you save a local copy of your stat changes.

## 🚧 TODO

In the future we will have these features:

* Sharing stats via an ID rather than exporting from ingame

In the future we are *considering* these features:

* Ingame stat editor UI
* Pull requests for balance changes that will be automatically synced in the main game
* Allow multiple collaborators in a single save file
* Accepted balance changes awarded with a special ingame nametag

If you would like any features added, please tell us in the discord!
