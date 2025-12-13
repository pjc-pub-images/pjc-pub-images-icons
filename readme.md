# pjc-pub-images-icons
# PUBLIC REPO

some sites require that icons are available as hosted files
this repo satisfies that requirement

how to 

```bash
# this is the shortform that works
https://raw.githubusercontent.com/<username>/<repo>/<branch>/avatar.png


# if you actually click 'raw' in the web interface to gihub you'll see this form
# the addition of .../refs/heads/... was a github change but they maintain the shortform
# without the .../refs/heads/... because it is obviously visually less noisy
https://raw.githubusercontent.com/<organization>/repo/refs/heads/<branch>/avatar.png


```

example:
```bash
# for the readme.md in root of repo 'pjc-pub-images-cons'
https://raw.githubusercontent.com/pjc-pub-images/pjc-pub-images-icons/refs/heads/main/readme.md


```

to check if the url and image are correct, try:
```bash

curl -I https://raw.githubusercontent.com/pjc-pub-images/pjc-pub-images-icons/refs/heads/main/readme.md
```
