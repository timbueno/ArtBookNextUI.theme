# NextUI Theme Template

This repository contains a template for creating themes for NextUI devices.

## Directory Structure

- `manifest.json` - Theme metadata and file mappings
- `preview.png` - Theme preview image (replace with your preview)
- `Wallpapers/` - Background images for all screens
  - `SystemWallpapers/` - Main menu backgrounds
  - `ListWallpapers/` - System-specific backgrounds
  - `CollectionWallpapers/` - Collection-specific backgrounds
- `Icons/` - Icons for systems, tools, and collections
  - `SystemIcons/` - System and main menu icons
  - `ToolIcons/` - Tool-specific icons
  - `CollectionIcons/` - Collection-specific icons  
- `Fonts/` - Font replacements and backups
- `Overlays/` - System-specific overlays

## Getting Started

1. Replace the placeholder `preview.png` with a 640×480 preview of your theme
2. Update the `manifest.json` with your theme information (name, author, etc.)
3. Add your wallpapers, icons, fonts, and overlays to their respective directories
4. Update the `content` section in `manifest.json` to reflect what your theme includes. Specifically, set content to `true` or `false` depending on what you're including.
5. Update your README.md if you want. You can also update your license if you want.
6. When complete, commit your changes and push.
7. Share your `.theme` repo with the NextUI community!

## Important Files

### Wallpapers

- `Wallpapers/SystemWallpapers/Root.png` - Main menu background
- `Wallpapers/SystemWallpapers/Recently Played.png` - Recently played list background
- `Wallpapers/SystemWallpapers/Tools.png` - Tools menu background
- `Wallpapers/SystemWallpapers/Collections.png` - Collections menu background
- `Wallpapers/SystemWallpapers/Game Boy Advance (GBA).png` - Main menu background for specified system (include tag)
- `Wallpapers/ListWallpapers/Game Boy Advance (GBA)-list.png` - System-specific background for list of games (include `-list.png` after tag)

### Icons

- `Icons/SystemIcons/Collections.png` - Collections menu icon
- `Icons/SystemIcons/Recently Played.png` - Recently played icon
- `Icons/SystemIcons/Tools.png` - Tools menu icon
- `Icons/SystemIcons/Game Boy Advance (GBA).png` - System-specific icon (include tag)

## For more information, see the [full theme documentation.](https://github.com/Leviathanium/NextUI-Theme-Manager/blob/main/documents/THEME_BUILDING.md)


