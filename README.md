# slide2md


## create your own environemnt
```{sh}
conda create --name r4e-slide2md python=3.6
conda activate r4e-slide2m

# install pptx2md
git clone https://github.com/ssine/pptx2md.git
cd pptx2md
pip install pptx2md
pip install --upgrade pptx2md

# installation done!
```

## convert .pptx to .md
```{sh}
# navigate to the working folder
pptx2md -t file.pptx -o file.md

```
