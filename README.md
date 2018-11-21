# karabiner-profile-switch
A simple CLI tool to switch between Karabiner-Elements profiles in the JSON configuration file

> Note (end of 2018): this tool is probably no longer needed. KE has the list of profiles in the tray icon menu.

This is a temporary solution for [Karabiner Elements](https://github.com/tekezo/Karabiner-Elements) for macOS Sierra.

Currently configuration changes are made in a JSON file, and to make things easier this tool will set
the `selected` profile in the JSON file. This eliminates the need to edit the JSON file manually when disconnecting 
or reconneting input devices that require different configuration.

**TODO**: Auto-restart Karabiner-Elemenets.

# Installation

```
npm i -g karabiner-profile-switch
```

# Usage
```
# kps
```

### Example with output:
```sh
$ kps
Karabiner-Elements profiles:
    1) Internal Keys
 -> 2) Apple USB Keys
Please select profile number: 1
Setting active profile: Internal Keys
Saving data...
Done.
```
