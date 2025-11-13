# Installisasi Waydroid di Linux Fedora

### 1. Langkah Pertama

```
sudo dnf install waydroid
```

```
sudo waydroid init -s GAPPS -c https://ota.waydro.id/system -v https://ota.waydro.id/vendor
```

```
sudo systemctl enable waydroid-container
```

```
sudo systemctl start waydroid-container
```

```
sudo systemctl status waydroid-container
```

```
waydroid show-full-ui
```
