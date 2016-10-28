# heroku-app-manager
Rails 5
Ruby 2.3.1


If you haven't setup ruby 2.3.1 it might cause some gem issues and SSL errors. I was able to get ruby to install by:

```
gem sources -r https://rubygems.org
gem sources -a http://rubygems.org
gem update --system
gem sources -r http://rubygems.org
gem sources -a https://rubygems.org
```

It is the gem update --system that is what you are after. I had to go to the non ssl source to get it to run without looking for a cert that was not working.


