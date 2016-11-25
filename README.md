## Installation
1. Tool / Install Packages
2. Tools / Command Pallete <kbd title="Shift+Command+P">⇧⌘P</kbd>  -> `Package Control: Install Packages`

## Packages
- kkga/spacegray https://github.com/kkga/spacegray
- spadgos/sublime-jsdocs https://github.com/spadgos/sublime-jsdocs

# Sublime settings
`Preferences` > `Settings - User`
```json
{
    "theme": "Spacegray.sublime-theme",
    "color_scheme": "Packages/Theme - Spacegray/base16-ocean.dark.tmTheme",
    "font_size": 13,
    "scroll_past_end": true,
    "tab_size": 4,
    "translate_tabs_to_spaces": true,
    "word_wrap": true
}
```

# 4 `space` tabs

## Reasons:

1. If we use space its always constant unlike tab size for tabs
2. Its homogeneous while having inline indentation

  ```
something   = oops
foo         = bar 😛

something	=	oops
foo			=	bar 😛
  ```
