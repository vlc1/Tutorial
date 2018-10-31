VCS (Version Control System)

1. SVN
1. Mercurial
1. Git
1. Darcs

# Commandes utiles

## Étape 1

```bash
git init
git status -s
git add README.md
git status -s
git commit -m "Initial commit"
git log
```

## Étape 2

```bash
vi test.f90
gfortran test.f90
./a.out
vi .gitignore
git add test.f90 .gitignore
git commit -m "Hello World fortran example"
vi README.md
git add README.md
git commit --amend
```

## Étape 3

```bash
git checkout -b mohamed
git branch -a
git diff
```

