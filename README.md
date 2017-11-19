# ABSS
## About
ABSS or Adult Block Site Script is a script you can use to block adult sites at
a time. You can save adult sites in file `list/sites.txt`, the site is not
include subdomain or folder just main domain like `http://example.com/` or
`example.com`.

## Dependency
- Iptables

## How to Use
1. Clone this repo or Download
2. Extract, and then open with terminal
3. Run `sudo bash install`
4. Check rules with command `sudo iptables -L --line-number`

example:
```
Chain INPUT (policy ACCEPT)
target     prot opt source               destination
LOG        all  --  46.166.167.16        anywhere             LOG level warning prefix "46.166.167.16"
DROP       all  --  46.166.167.16        anywhere
```

## To Do
in Project
