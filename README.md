# com.nfynt.wvp

[![npm version](https://badge.fury.io/js/com.nfynt.wvp.svg)](https://badge.fury.io/js/com.nfynt.wvp)

### Unity Web Video Player

A video player plugin for Unity WebGL applications. Unity's builtin VideoPlayer generally doesn't work for WebGL or is not supported on mobile browsers. This package uses Web-native video elements to read the video source and exposes the basic video controls to Unity.
You can use video URLs either from `StreamingAssets` path or external web servers (permissing CORS). Video controls include - Start, Stop, Pause, Resume, (Un)Mute, and respective events within the editor. This package supports in-editor playing as well using Unity's VideoPlayer.

### Importing in Unity

To install this package in Unity you'll first have to add a new Scoped Registry. Head over to `Edit>Project Settings>Package Manager` and add the new registry details as follows - 
```
Name: npmjs
URL: https://registry.npmjs.org
Scope(s): com.nfynt
```

After this head to `Window>Package Manager` and select `My Registries` under the `Packages:` options. This will list all the available package on npm, find `Web Video Player` and select the latest version available and hit install 🚀.

### Issues
Submit issues on [Github Repo](https://github.com/nfynt/com.nfynt.wvp/issues) with appropriate label as `bug\enhancement\help wanted`.

### Authors
```
Shubham
```
