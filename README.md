# Welcome

This is a repository made to explore different functionalities in group projects

## VSCode Personalization

Because this project does not contain any kind of code most of the VSCode Extensions installed will be used to enhance the visual experience while usign the editor

<details>
  <summary> Visual Enhance Extensions </summary>

* [Indent Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
* [Rainbow brackets](https://marketplace.visualstudio.com/items?itemName=2gua.rainbow-brackets)
* [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

</details>

<details>
  <summary> Useful Extensions </summary>

* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
* [Markdown Preview](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

</details>

<details>
  <summary> Other Extensions i have found useful </summary>

* [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
* [Turbo Console Log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log)
* [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
* [Code time](https://marketplace.visualstudio.com/items?itemName=softwaredotcom.swdc-vscode)
* [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)
* [CodeSnap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)

</details>

## Setup .gitconfig

On the other hand before usign this i will setup the global git enviroment of my computer to follow some restrictions 

First of all i always want the base branch in a git repository to be called main but i downloaded git without making this restriction, so i will use the following command instead

```
git config --global init.defaultBranch main
```

I also have some commands i use but they are kind of a pain in the back to type, so i will create some aliases to allow me execute them faster and more conveniently *(alias are personalized commands that we can specify in the global git configuration)*

**Disclaimer:** i didn't come up with this aliases on my own they were provided by Klerith [Original Gist](https://gist.github.com/Klerith/0acf18bbece7923bcac55edb71b03c2b) you are welcomed to check more of his gist and the udemy course where i found this and other useful information [Git+Github Udemy](https://www.udemy.com/course/git-github/)

```
git config --global alias.s "status -sb"
```

```
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold cyan)%h%C(reset) - %C(green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
```

After all the configurations are set we can check for errors, make any modifications and look at the configuration global file using

```
git config --global -e
```


