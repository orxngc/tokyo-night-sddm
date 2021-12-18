<h2 align="center">🗼 Tokyo Night SDDM 🗼</h2>

<p align=center>
A Tokyo Night theme for the <a href="https://github.com/sddm/sddm">SDDM Login Manager</a>
</p>

<h2 align=center>Preview</h2>
<center>
<img src="./Previews/preview.png" alt="preview-1">
<details>
<summary>More Previews</summary>
<img src="./Previews/preview-shacks.png" alt="preview-2">
<img src="./Previews/preview-tokyo-city.png" alt="preview-4">
<img src="./Previews/preview-path.png" alt="preview-3">
</details>
</center>

## Install

> _Assumes that you've installed and configured SDDM correctly_ (if not [read more](https://wiki.archlinux.org/title/SDDM))

1. Open terminal, and clone the repository with:

   ```sh
   git clone https://github.com/rototrash/tokyo-night-sddm.git ~/tokyo-night-sddm
   ```

2. Them move it as follows:

   ```sh
   sudo mv ~/tokyo-night-sddm /usr/share/sddm/themes/
   ```

### Common Step

Edit the `/etc/sddm.conf` (with any text editor with **raised** privileges, so that it looks like this:

```sh
sudo nano /etc/sddm.conf  # use any text editor with raised privileges
---
[Theme]
Current=tokyo-night-sddm
   ```

## Language and time format

- You can also change the time format.
- To change the default wallpaper put desired image in the `tokyo-night-sddm/Backgrounds/` folder and add the name of the image followed by its extension (`.jpg` or `.png`) in `theme.conf` file.
- You can also customize it further if you wish in the `theme.conf`
(blur, form position, etc).
## Credits

Based on the theme [`Sugar Dark for SDDM`](https://github.com/MarianArlt/sddm-sugar-dark) by **MarianArlt**.

## License

[GNU Lesser General Public License v3.0](LICENSE)