# Firefox userChrome
Custom Firefox files with a focus on minimizing visual UI elements until it's needed. Autohide Everything!

Only works with Sidebery installed - Sidebery Extension Required
https://github.com/mbnuqw/sidebery

Compatible with Firefox 139 as of 2025/05/28   
Not Compatible with versions below

## Features:
- Autohide Main Toolbar
- Autohide Sidebery
- Hide/Unhide native tab bar when Sidebery is active ( Sidebery preface setting not required anymore )
- Shows Full Sidebery when maximized if screensize is > 1200px wide ( Adjustment required for user specific screen size )
- `userConfig.css` Consolidated adjustments of Personal Preferences here for conevenience
- `userColors.css` Added for convenient Color Profile adjustments/removal (Inspired by Flowlauncher Theme Named Tokyo Night Storm)
- `sideberyConfig.css` Added to consolidate Sidebery cosmetic modifications/fixes
- `uc.shadow.flicker` Added Cool aesthetic indicator for overflowing tabs in Sidebery. Flickers like a real fluorescent light. Off by default. It's a resource hog to animate.
#### `about:config` toggles to add
```
  //Toggle for Chromeless Experience
  uc.chromeless

  //Toggle for Collapsed Tabs when Maximized
  uc.collapse.tabs

  //Toggle for Full Tabs when Windowed
  uc.full.tabs

  //Toggle for Shadow Flicker
  uc.shadow.flicker
```
#### `about:config` settings to set
```
  toolkit.legacyUserProfileCustomizations.stylesheets = true
  sidebar.verticalTabs = false
  sidebar.revamp = false
  widget.windows.mica = false

  // as of version 138, it's default is '2', turning on mica for content popup menu
  widget.windows.mica.popups = 0

```

## Default Functionality


https://github.com/user-attachments/assets/4f3f6a3c-50bd-4f49-8739-b67d5778b2f4

## Chromeless Experience



https://github.com/user-attachments/assets/44c52ca7-903c-4c5c-ab6e-5e89b019131e
