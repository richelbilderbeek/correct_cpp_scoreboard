# FAQ

## Where is this scoreboard for?

This scoreboard is for students of [the Correct C++ course](https://github.com/richelbilderbeek/correct_cpp).

## How do I use this scoreboard?

See [use the scoreboard](https://github.com/richelbilderbeek/correct_cpp/blob/master/use_the_scoreboard.md).
 
## The original scoreboard has changed, how do synchronize my fork with the original?

From:

  * [GitHub Help: Configuring a remote for a fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/)
  * [GitHub Help: syncing a fork](https://help.github.com/articles/syncing-a-fork/)

In your fork's location, do once:

```
git remote add upstream https://github.com/richelbilderbeek/correct_cpp_scoreboard
```

In your fork's location, then do each time you want to sync:

```
git fetch upstream
git checkout master
git merge upstream/master
```
