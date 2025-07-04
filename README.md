# Omarchy

Turn a fresh Arch installation into a fully-configured, beautiful, and modern web development system based on Hyprland by running a single command. That's the one-line pitch for Omarchy (like it was for Omakub). No need to write bespoke configs for every essential tool just to get started or to be up on all the latest command-line tools. Omarchy is an opinionated take on what Linux can be at its best.

Read more at [omarchy.org](https://omarchy.org).

## License

Omarchy is released under the [MIT License](https://opensource.org/licenses/MIT).

## New Install

```bash
eval "$(wget -qO- https://raw.githubusercontent.com/timkuntz/omarchy/refs/heads/master/boot.sh)"
```

This will clone the `timkuntz/omarchy` fork and switch to the branch `mac-arm-setup` prior to installation.

I will leave the `master` branch as a clean fork (except for this file) so you can always change branches to return to the original Omarchy setup.
```
cd ~/.local/share/omarchy
git switch master
```
```

