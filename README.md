# ComfyUI extension

## Touchpad two-finger gesture support for macOS

adds detection of using touchpad or mouse. It will fallback to the original processMouseWheel behaviour when using mouse. This detection only works when using macOS Safari and enabling the "natural scroll" feature of touchpad on macOS.

fixes https://github.com/comfyanonymous/ComfyUI/issues/2059

- two-finger scrolling (vertical and horizontal) to pan the canvas
- two-finger pinch to zoom in and out
- command-scroll up and down to zoom in and out


### Installation

1. Put this folder into ComfyUI/custom_nodes/TinkerBot-tech-for-ComfyUI-Touchpad
2. Restart ComfyUI
3. Reload the UI
4. Enjoy!
