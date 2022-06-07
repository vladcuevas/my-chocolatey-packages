# my-chocolatey-packages

I like to have my applications with the latest version, but I'm tired to be installing and updating them myself, therefore I'm starting to use chocolatey in Windows and Homebrew in Mac to manage the packeges/applications for me.

Export all currently installed packages to a file.

```ps1
choco export
```

This is especially helpful when re-building a machine that was created using Chocolatey. Export all packages to a file, and then re-install those packages onto new machine using:

```ps1
choco install packages.config
```
