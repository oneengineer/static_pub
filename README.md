# Flutter Static Files for CDN

This repository hosts Flutter static files for CDN acceleration in China.

## CDN URLs

### JSDMirror (China-friendly, recommended)

| Resource | URL |
|----------|-----|
| CanvasKit | `https://cdn.jsdmirror.com/gh/oneengineer/static_pub@main/canvaskit/` |
| Fonts | `https://cdn.jsdmirror.com/gh/oneengineer/static_pub@main/fonts/` |

### jsDelivr (Global)

| Resource | URL |
|----------|-----|
| CanvasKit | `https://cdn.jsdelivr.net/gh/oneengineer/static_pub@main/canvaskit/` |
| Fonts | `https://cdn.jsdelivr.net/gh/oneengineer/static_pub@main/fonts/` |

## Files Structure

```
static_pub/
├── canvaskit/              # Flutter CanvasKit (~20MB)
│   ├── canvaskit.js
│   ├── canvaskit.wasm
│   ├── chromium/
│   │   ├── canvaskit.js
│   │   └── canvaskit.wasm
│   ├── skwasm*.js/wasm
│   └── web/fonts/
└── fonts/                  # Custom fonts (~57MB)
    ├── NotoSansSC-VariableFont_wght.ttf
    ├── NotoColorEmoji-Regular.ttf
    ├── ZCOOLQingKeHuangYou-Regular.ttf
    ├── MaShanZheng-Regular.ttf
    └── Roboto-*.ttf
```

## Flutter Version

- Flutter 3.35.6
- Engine Revision: d2913632a4578ee4d0b8b1c4a69888c8a0672c4b

## Last Updated

2025-12-09 23:41:53
