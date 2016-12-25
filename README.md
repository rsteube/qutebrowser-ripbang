# qutebrowser-ripbang

Userscript that adds a [DuckDuckGo bang](https://duckduckgo.com/bang) as local searchengine.

## Install

1. Install `requests` using pip or system package manager:
  ```bash
  pip2 install requests
  ```
  
2. Place the script at `~/.local/share/qutebrowser/userscripts/ripbang`


## Usage

```
:spawn --userscript ripbang {bang}

```

## Example

```sh
# ./ripbang amazon maps wa
!amazon https://www.amazon.com/s/?tag=duc0c-20&search-alias%3Daps&field-keywords={}
!maps https://maps.google.com/maps?hl=en&q={}
!wa https://www.wolframalpha.com/input/?i={}
```

