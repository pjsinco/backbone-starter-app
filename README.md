# Starter template for projects

**Configure package.json and install the packages:**
```bash
sudo npm install
```
**Configure Gruntfile.js**

**If using Compass, configure config.rb**

**Install Susy, Compass Normalize**
```bash
gem install susy
gem install compass-normalize
```

**Add livereload script to bottom of jade files**
```markup
script(src='http://localhost:35729/livereload.js')
```

**Add symbolic links in components/js/node_modules:**
```
ln -sf ../views
ln -sf ../models
ln -sf ../collections
```

**Maybe update Sass**
```bash
gem update sass
```

**Using a Bower package?**
See the .bowerrc file

```bash
bower init
```

###[Backbone cheat sheet](http://www.igloolab.com/downloads/backbone-cheatsheet.pdf)

