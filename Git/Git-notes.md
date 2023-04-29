# Git Notes
## Site
https://support.github.com/

## Git Desktop
https://desktop.github.com/
https://central.github.com/deployments/desktop/desktop/latest/win32

## Config
```bash
# view
git config user.name
git config user.email
# set
git config --global user.name <myname>
git config --global user.email <myemail>
```

## Creat Repo
```bash
mkdir -pv git-study
cd git-study
git init
```

## Areas
- Working
- Stage - `git add` - (faster, mmap, eg. git diff)
- Repo - `git commit`
