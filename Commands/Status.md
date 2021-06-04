# git status

This command `git status` is extremely helpful when it comes to checking on the, you guessed it, status of your repository.

Using `git status` will show you what changes are being tracked, aren't being tracked, what [commits](./Commit.md) need to be [pushed](./Push.md)/[pulled](Pull.md), etc. It is exactly what it sounds like, a status check.

Status is a command that is safe to use at any time.

If you want to see what it going one it's good to use `git status` in between commands until you get to know the flow better.

```
git add .
git status

git commit -m "Modified landing page"
git status

git push
git status
```

## Resources

- [Git Remote Documentation](https://git-scm.com/docs/git-status)

---

[Back to home](../README.md)
