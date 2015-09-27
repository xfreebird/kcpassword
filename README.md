# kcpassword
OS X autologin enabler utility based on script from [osx-vm-templates](https://github.com/timsutton/osx-vm-templates/blob/master/scripts/autologin.sh)

# How to install ?

```shell
brew tap xfreebird/utils
brew install kcpassword
```

# Usage

To enable OS X autologin for user:

```shell
enable_autologin "username" "password"
```

You also can create ```/etc/kcpassword``` file with the password, ```enable_autologin``` script invokes this command:

```shell
enable_autologin "password"
```


