# onedwm
merge multi patch as one patch for dwm
-------
## dwm version
  - commit: `2a28c31` 
  - version `6.3`
-------
## use
  - get **dwm** `6.3`
  - download any patch like: `$ wget https://raw.githubusercontent.com/one-patch/onedwm/master/patchs/1000.diff`
  - patch by: `$ patch -p1 < 1000.diff` 
-------
## available
  - [x] [1](https://raw.githubusercontent.com/one-patch/onedwm/master/patchs/1000.diff): padding pertag stack<->master notitle status2d pango

--------
## how to contribute
  - get **dwm** `6.3`
  - apply some important patch without any person config
  - extract one patch from last commit `xxxxxx` to `2a28c31`
  ```bash
  $ git diff 2a28c31..xxxxxx > new_onepatch
  ```
  - create pull request by fork or modifie `patchs/onepatch.diff` in this repo by `github` editor
  

