# Optimistic Nihilistic blog

## note to self:

Unlike your _other_ blog, you don't need to checkout the `source` branch for this one. 
Instead, work on `master` and push as usual. To deploy, do: `git push deploy master` and 
the digital ocean droplet git hook should kick in and update the site... Go ahead, try it now, 
I'll wait here...  

Oh right - you probably noticed you also have to do this if you're on a new machine:  

```
git remote add deploy user@ip.of.server.box:~/repo-name.git
```

There you go!
