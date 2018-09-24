# RibbonBuilder
![RibbonBuilder](https://raw.githubusercontent.com/nadnerb33/RibbonBuilder/master/Images/RibbonBuilder.png)

A MapBasic tool that builds a custom ribbon interface within Mapinfo Pro which can contain any number of datasets, tools or standard MI Pro functions/commands all easily configured via a simple spreadsheet and therefore requires absolutely no MapBasic coding.
The tool has 2 major functionalities:

1.	Allows the administrator to configure a one-stop-shop for all frequently used datasets by the organisation – essentially a ‘Favourites’ list. This ensures all users in the organisation or team are using the same data sources and don’t have to spend time navigating around file systems looking for the correct files.

2.	Allows the administrator to configure which tools are automatically loaded on all users MI Pro instances ensuring all users are running the same, up to date versions of all tools. When new MI Pro installations are made the process of adding all the required tools is as simple as adding RibbonBuilder and setting it to AutoLoad.


# Usage

1. Copy [Config_example.xlsx](Config_example.xlsx) or [Config_template.xlsx](Config_template.xlsx) and rename to Config.xlsx
2. Configure Config.xlsx (see comments in column headers on each tab)
3. Add [RibbonBuilder64_Launcher.MBX](RibbonBuilder64_Launcher.MBX) to the MI Pro Tool Extensions and set to AutoLoad.

For more detailed usage instructions and further information please see [RibbonBuilder_Readme.pdf](RibbonBuilder_Readme.pdf)
