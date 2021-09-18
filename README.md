## Wireshark - AppImage

![pngwing com](https://user-images.githubusercontent.com/90393971/133905505-306e0b2a-e704-4f88-a889-699e19832202.png)

1. Download pkg2appimage tool and make it executable.
   ```shell
   wget https://github.com/sagarkhandve/Wireshark/releases/download/v3.4.8/Wireshark.AppImage
   chmod +x Wireshark-3.4.4.AppImage
   ```
2. Run:

   ```shell
   sudo ./Wireshark.AppImage
   ```

A configuration for [pkg2appimage](https://github.com/AppImage/pkg2appimage) to build Wireshark in AppImage form.

How to use it?

1. Clone this repository and `cd` into it.
    ```shell
    git clone https://github.com/sagarkhandve/Wireshark.git
    cd Wireshark/
    ```
2. Download pkg2appimage tool and make it executable.
   ```shell
   wget https://github.com/AppImage/pkg2appimage/raw/master/pkg2appimage
   chmod +x pkg2appimage
   ```
3. Build it:

   ```shell
   ./pkg2appimage Wireshark.yml
   ```

4. After a short break you should get an executable inside `out/` directory.

