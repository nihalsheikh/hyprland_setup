# Arch Hyprland Setup

### Follow the below instructions to install hyprland
I have already arch installed, so i'm installing hyprland from gnome

- [x] Make sure to keep your system up to date
    `sudo pacman -Syu`

- [x] Add the necessary packages for installation
    i like `Kitty` terminal, `Nautilus` File Manager (Gnome's Default) `Chrome` Browser as default and some other packages and fonts...
    ```
    sudo pacman -S hyprland hyprpaper hyprlock hypridle wofi \
    xdg-desktop-portal-hyprland xdg-desktop-portal-gtk \
    kitty google-chrome nautilus \
    grim slurp wl-clipboard \`
    brightnessctl playerctl pamixer \
    ttf-font-awesome ttf-jetbrains-mono \
    polkit-gnome gnome-keyring \
    network-manager-applet bluez bluez-utils \
    pipewire pipewire-alsa pipewire-pulse wireplumber \
    qt5-wayland qt6-wayland
    ```

- [x] Download Waybar
    `sudo pacman -S waybar`
