# One Dark (Pro) for Kate

> Atom's iconic One Dark theme for [Kate Editor](https://kate-editor.org/) (and any katepart application, such as [KWrite](https://www.kde.org/applications/utilities/kwrite/), [Kile](http://kile.sourceforge.net/), and [KDevelop](https://www.kdevelop.org/)).

## Details

These files provide color themes and syntax highlighting for Kate editor. Kate is the
embedded KDE editor used within Kdevelop, Kile, Kwrite, etc. The color changes will be
applicable to all KDE programs with editor components.

**NOTE:** By default, this theme sets the font as `Fira Code` which may need to be
downloaded and installed from [their repository](https://github.com/tonsky/FiraCode).

This theme is "bare": It provides generic colors but does not handle various
language-specific syntax highlighting. There are likely many bugs and issues with things
being improperly highlighted. Submitting an issue is greatly appreciated. One day, this
repo may include highlighting that's specifically tailored to common languages.

### Color Palette

#### Stylized

![Color Reference](https://raw.githubusercontent.com/joshdick/onedark.vim/master/img/color_reference.png)

#### Full List

| NAME         | CLASSIC   | VIVID     |
| ------------ | --------- | --------- |
| purple       | `#c678dd` | `#d55fde` |
| error        | `#f44747` | `#f44747` |
| coral        | `#e06c75` | `#ef596f` |
| whiskey      | `#d19a66` | `#d19a66` |
| chalky       | `#e5c07b` | `#e5c07b` |
| lightDark    | `#7f848e` | `#7f848e` |
| dark         | `#5c6370` | `#5c6370` |
| malibu       | `#61afef` | `#61afef` |
| green        | `#98c379` | `#89ca78` |
| fountainBlue | `#56b6c2` | `#2bbac5` |
| invalid      | `#ffffff` | `#ffffff` |

## Installation

### Using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```sh
git clone https://github.com/zachhardesty7/kate-one-dark.git
```

### Manual

Download using the
[GitHub .zip download](https://github.com/zachhardesty7/kate-one-dark/archive/master.zip)
option and unzip them.

### Activation

In Kate's settings, go to _"Fonts and Colors"_ and click _"Import"_ to import the schema.

## Attributions

This theme is based on
[Atom's One Dark theme](https://github.com/atom/atom/tree/master/packages/one-dark-ui)
but uses [onedark.vim](https://github.com/joshdick/onedark.vim) as a base reference.
The eventual end goal of the theme targets
[One Dark Pro](https://github.com/Binaryify/OneDark-Pro).

## License

[MIT License](./LICENSE)
