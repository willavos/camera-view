# CameraView

```
   ___                                       _
  / __\__ _ _ __ ___   ___ _ __ __ _  /\   /(_) _____      __
 / /  / _` | '_ ` _ \ / _ \ '__/ _` | \ \ / / |/ _ \ \ /\ / /
/ /__| (_| | | | | | |  __/ | | (_| |  \ V /| |  __/\ V  V /
\____/\__,_|_| |_| |_|\___|_|  \__,_|   \_/ |_|\___| \_/\_/
```

## Usage:
  Append URL parameters to control the embedded video.

## Parameters:
1. `?video=sheep|reef|ospreys|jellyfish|fish|eagles|africa`: Select a predefined video by name.
2. `?code=<YouTubeVideoId>`: Override the video with any valid YouTube ID (takes precedence over ?video).
3. `?mute=1|0`: 1 (default) mutes to allow autoplay; 0 requests sound (autoplay may be blocked until user interacts).

## Examples:
- `cameraview.html?video=reef`
- `cameraview.html?video=ospreys&mute=0`
- `cameraview.html?code=K380RGUXHsw&mute=1`

## Using this quickly
GitHub pages are turned on for this repo, so just hit this URL: `https://willavos.github.io/camera-view/cameraview.html`

## Notes:
  Autoplay with sound can be blocked by browser policies; keep mute=1 for reliable autoplay.
  If you need sound immediately, user must interact (click/tap) before unmuting via the YouTube IFrame API.
