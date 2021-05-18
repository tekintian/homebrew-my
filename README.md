My homebrew repo.

Well, the boost@1.59 has been disabled.see

If we still need it, we can build our own brew repo.

I have create a repo which checked boost@1.59.rb out from offical repo and enable it.

Then open the terminal, include your repo brew tap [user]/[repo] [url] and install it.

e.g.

brew tap tekintian/my https://github.com/tekintian/homebrew-my.git

brew update

brew search boost@1.59
> jokersun/my/boost@1.59 ✔

brew install tekintian/my/boost@1.59
