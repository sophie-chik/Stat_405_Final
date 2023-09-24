version https://git-lfs.github.com/spec/v1
oid sha256:8131639f4bf7e9e7430c9a530c3f8db05e95e3c1d46507a4dd639061b077c4c5
size 1967


### Instructions on installing LFS: 
1. If you have brew, open terminal and run: `$ brew install git-lfs`  
1. If not, [Install LFS](https://git-lfs.com/) and follow instructions   
1. If not, [Install LFS](https://git-lfs.com/) and follow instructions.   

1. Again on your terminal, run: `$ git lfs install `  
Should say: ` Git LFS initialized.`  

You should be good to go! 
You should be good to go!  
If you're having any problems, check out [LHS Docs Page](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage/)

### General Git Instructions:
1. If this is your first time working with this project, you'll need to clone it. First copy the [link of the repo](https://github.com/sophie-chik/Stat_405_Final), then go in your terminal and type `$ git clone https://github.com/sophie-chik/Stat_405_Final`. 
1. **Before you work on anything, always make sure to pull by `$ git pull`.** This ensures that you're working with the latest version of the code and will not have any issues pushing your changes. 
1. Once you're done working on something (recommended to do this often), type `$ git status` to check the files you have edited and make sure it looks right.
2. Now, you need to add the files whose changes you want to commit. Do this by either doing `$ git add /path/to/file` or if you want all the changes committed, do `$ git add -A`.
3. You can double check your changes have been added by again doing `$ git status`.
4. Now, you need to commit your changes. Do this with `$ git commit -m "USEFUL commit message"`.
5. Last step! You have to push your changes, which basically uploads it to github. Just type `$ git push` in your terminal. It will show a progress bar, so you'll know when it has been pushed (should not take more than a couple seconds).
6. It's good practice to check your repository on github and make sure the changes have actually been pushed.
