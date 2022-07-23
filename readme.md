# gitconfig

Cherry pick parts from this repository for your own config.  
Assuming you've cloned this repository to `~/project/gitconfig` add
these lines to your `~/.gitconfig`:

```conf
...
[include]
  path = ~/project/gitconfig/core.conf
  path = ~/project/gitconfig/alias.conf
  path = ~/project/gitconfig/pretty.conf
...
```
Or use all of it.

```.gitconfig
...
[include]
  path = ~/project/gitconfig/main.conf
...
```
