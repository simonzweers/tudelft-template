# TU Delft LaTeX template with circuits

To run it locally, install the following packages:

```bash
sudo dnf install inkscape texlive texlive-{amsmath,tcolorbox,svg,circuitikz,minted,roboto,ucs,todonotes,titling,blindtext,sectsty,tikzpagenodes,helvetic} python3
```

One-liner to get all files in the current directory:

```
wget https://github.com/simonzweers/tudelft-template/archive/refs/heads/main.zip && unzip main.zip -d . && cp -r tudelft-template-main/* ./ && rm main.zip && rm -rf tudelft-template-main/
```
