# Nitro Type - Top Team Requirements Table

This repository contains a userscript that adds a Top Team Requirements table to the [Nitro Type](https://www.nitrotype.com/)
team page. This table show statistics about the top 100 teams on Nitro Type. This information can be useful for team leaders who want to see how many races their members need to complete for their team to reach the top 100.

## Installation

1.  Install a userscript manager for your browser. For example, [Tampermonkey](https://tampermonkey.net/) for Chrome or [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) for Firefox.
2.  Go to the [Nitro Type - Top Team Requirements Table](https://greasyfork.org/en/scripts/473519-nitro-type-show-daily-races) script page.
3.  Click the Install button.
4.  Go to your Nitro Type team page and refresh the page.
5.  You should now see a new table named **Top Team Requirements** below the **Team Rankings** table.

## Uninstallation

To uninstall the userscript, simply disable or remove it from your userscript manager.

## How it works

The script fetches weekly season and leaderboard information from the [NitroType API](https://www.nitrotype.com/api/v2). It then calculates this data and displays the results in a table. Finally, this table is injected under the **Team Rankings** table on the team page.

## Screenshot

![image](https://github.com/rickstaa/nitro-type-top-team-requirements-table/assets/17570430/5606744a-79b7-4278-a23e-8536a69521dd)

## Bugs and contributions

If you find a bug or have a suggestion for how to improve the script, please open [an issue](https://github.com/rickstaa/nitro-type-daily-races/issues) or submit a [pull request](https://github.com/rickstaa/nitro-type-daily-races/compare) on GitHub. We welcome contributions from the community and appreciate your feedback 🚀. Please consult the [contribution guidelines](CONTRIBUTING.md) for more information.
