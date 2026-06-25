# PyDev Wheelhouse

Static package registry for the PyDev iOS/macOS app.

## App catalog

Use this catalog URL in PyDev Packages:

```text
https://raw.githubusercontent.com/zhiluo20/pydev-wheelhouse/main/catalog/v1/index.json
```

Runtime installs are restricted to hash-checked pure Python `none-any` wheels. Native iOS wheels are published here for development and signed app payload packaging only; the app will not install them at runtime.

## Counts

- Pure Python runtime wheels: 17
- iPhoneOS / iPhone Simulator development wheels: 18

## Layout

```text
catalog/v1/index.json
simple/<package>/index.html
simple-ios/iphoneos/<package>/index.html
simple-ios/iphonesimulator/<package>/index.html
wheels/pure-python/*.whl
wheels/ios/iphoneos/*.whl
wheels/ios/iphonesimulator/*.whl
```
