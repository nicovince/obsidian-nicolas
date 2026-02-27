## Obsidian
### Setup git synchro
https://medium.com/technology-hits/how-to-sync-obsidian-across-all-devices-using-git-automatically-and-for-free-dd3c76e7447b
- obsidian git plugin on desktop
- gitsync app on android device
	- Configure to pull/push on open/close
### setup icon
https://forum.obsidian.md/t/obsidian-app-icon-doesnt-show-up-in-taskbar-on-linux/48658/5
```bash
cat ~/.local/share/applications/obsidian.desktop <<EOF
[Desktop Entry]  
Name=Obsidian  
Exec=/home/nicolas/.local/bin/Obsidian-1.11.7.AppImage  
Terminal=false  
Type=Application  
Icon=obsidian  
StartupWMClass=obsidian  
X-AppImage-Version=1.11.7  
Comment=Obsidian  
MimeType=x-scheme-handler/obsidian;  
Categories=Office;
EOF
```

```bash
```