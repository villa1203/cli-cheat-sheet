# cli-cheat-sheet

todo:
see exemple of resourcies?
[atlassian](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)
[atlassian / pdf]([https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf))
[git-tower](https://www.git-tower.com/blog/command-line-cheat-sheet/)

## git

### supprimer le fichier mais garder en local
``` bash
git rm --cached {file_name}
```

### supprimer le fichier de l'historique git
```bach
git filter-branch -f --index-filter 'git rm --cached --ignore-unmatch {file_name}'
```

Il faudra faire un push --force pour pousser sur le repo
