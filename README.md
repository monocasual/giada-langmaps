# giada-langmaps

This is the official repository of [Giada](https://www.giadamusic.com) **langmap files**. A langmap is a JSON file containing translation strings used for localization. Langmap files reside in your configuration directory, or more precisely:

* Linux — `/home/[your_user]/.giada/langmaps/`;
* OS X — `[your_home]/Library/Application Support/Giada/langmaps/`;
* Windows — `langmaps/` folder, alongside the binary file.

## How to install a langmap file

Download the zip archive and uncompress it in the langmap folders seen before. Giada will look into those directories on startup. If the files are valid langmap files they will be listed in the Configuration window, *Misc* section. 

## Contributing to a new translation

Clone this repository, make a copy of the original `english.langmap` file, save it as `[your-language].langmap` and then translate the strings in it. Please open a new Pull Request when you are done. 

Few things to keep in mind while translating strings in a langmap file:

* always save the langmap file in UTF-8 format;
* some strings may contain special characters such as `\n` (line break) or `{}` (formatting placeholder). Keep those special characters in place, Giada might crash otherwise.

For more information, please refer to the [official documentation](https://www.giadamusic.com/documentation-configuration).
