# Mi 9 AI Key -> Gemini (RisingOS)

This Magisk module remaps Xiaomi Mi 9 AI key scan code `689` to Android `ASSIST` key.

## What it does

- Replaces `system/usr/keylayout/gpio-keys.kl`
- Adds mapping:

```kl
key 689   ASSIST
```

On AOSP-like ROMs (including RisingOS), `ASSIST` triggers the current default assistant app.

## How to use with Gemini

1. Install Google Gemini app.
2. Set Gemini as default assistant app in system settings.
3. Flash this module in Magisk and reboot.
4. Press AI key to trigger assistant.

## Notes

- If your build does not react to `ASSIST`, try changing mapping to `VOICE_ASSIST`.
- This module is designed for Xiaomi Mi 9 keycode `689`.
