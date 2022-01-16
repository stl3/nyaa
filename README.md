# nyaa
cli tool for downloading torrents from [nyaa.si](https://nyaa.si), heavily inspired by [notflix](https://github.com/Bugswriter/notflix)

## Dependencies

* [pmenu](https://github.com/sgtpep/pmenu) - Dynamic terminal-based menu
* [webtorrent](https://github.com/webtorrent/webtorrent-cli) - Tool to download torrents
* [aria2](https://aria2.github.io/) - Lightweight alternative for webtorrent

## Usage

```sh
$ nyaa
$ nyaa -q "XYZ"         # Search for XYZ (otherwise show search prompt)
$ nyaa -d some-dir      # Download to somedir, defaults to $HOME/Downloads
$ nyaa -a               # Show remakes as well
```

## Installation

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/yaemiku/nyaa/main/nyaa" -o /usr/local/bin/nyaa
$ sudo chmod +x /usr/local/bin/nyaa
```

## License
This project is licensed under the GNU General Public License, version 3.

