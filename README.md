# nateandxtina.wedding

# Install Dependencies 
```shell
# Install ruby with rvm
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
\curl -sSL https://get.rvm.io | bash -s stable --ruby
```

# Build & Run
```shell
bundle install  
bundle exec jekyll serve -l --host=0.0.0.0   
# Use hostname -I to find IP serving IP
```

# Update deps
`bundle update` 
