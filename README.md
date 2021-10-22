# Razer Blade 15 Precision Touchpad Sensitivity Fix

## Windows 10/11 Registry patch

### About
This registry patch fixes the false input issues related to recent Razer Blade 15 laptops. Specifically, issues with the palm rejection implementation and the trackpad being off center of the keyboard.  This will desensitize/disable the far edges of the trackpad, solving the issue of mis-clicks, jumpy cursors, and maximize/minimize issues.

### Usage
- Apply the registry patch.
- Profit.

### Notes
Patch will work for almost all 2019+ Razer laptops.  Tweak values to suit your preferences.

### Registry keys added:

- SuperCurtainTop, 800
- SuperCurtainLeft, 800
- SuperCurtainRight, 1000
- SuperCurtainBottom, 800


### Reference
Microsoft Precision Trackpad Tuning Guide (https://docs.microsoft.com/en-us/windows-hardware/design/component-guidelines/touchpad-tuning-guidelines)
