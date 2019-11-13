# QGIS via Singularity

[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/3001)

## Fedora 29, QGIS v2.18 (Las Palmas)

No special instructions


## Fedora 31, QGIS v3.8 (Zanzibar)

In addition to any data directories you require, you also need to add the following to
bind-mount necessary system directories.

```--bind /run/user/$(id -u):/run/user/$(id -u)/ --bind /etc/machine-id:/etc/machine-id```

