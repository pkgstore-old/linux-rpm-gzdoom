# GZDoom

**ZDoom** is a family of enhanced ports (modifications) of the Doom engine for
running on modern operating systems. It runs on Windows, Linux, and OS X, and
adds new features not found in the games as originally published by id Software.

ZDoom features the following that is not found in the original Doom:

- Runs on all modern versions of Windows, Mac, and Linux distributions.
- Can play all Doom engine games, including Ultimate Doom, Doom II, Heretic, Hexen, Strife, and more.
- Supports all editing features of Hexen.
- Supports most of the Boom editing features.
- Supports new features such as colored lighting, 3D floors, and much more.
- All Doom limits are gone.
- Several softsynths for MUS and MIDI playback, including OPL softsynth for an authentitc "oldschool" flavor.
- High resolutions.
- Quake-style console and key bindings.
- Crosshairs.
- Free look.
- Jumping, crouching, swimming, and flying.
- Up to 8 player network games using UDP/IP, including team-based gameplay.
- Support for the Bloodbath announcer from the classic Monolith game Blood.
- Walk over/under monsters and other things.

GZDoom provides an OpenGL renderer and HQnX rescaling.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/gzdoom
$ dnf install -y gzdoom
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y gzdoom
```

## Remove

```
$ dnf erase -y gzdoom
$ dnf copr remove pkgstore/gzdoom
```

## Syntax

### Load WAD

```
gzdoom -file 'DOOM.WAD'
```
