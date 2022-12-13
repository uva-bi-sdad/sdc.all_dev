# data_center
A test repository where the public data repos are submodules, to see if we can generate dashboards more automatically

## Adding submodules
Follow [this link](https://github.blog/2016-02-01-working-with-submodules/), but generally

```shell
git submodule add https://github.com/<user>/rock rock
```

Also note that submodules are consistency > convenience, meaning there is an implicit assumption that this repository will push no changes to the submodules 

Can be possible to [push and update submoudles](https://stackoverflow.com/questions/5814319/git-submodule-push), too though
```
git push --recurse-submodules=on-demand
```
