# JWT authentication using Rails 7 with Devise

This is an improved version of https://github.com/voscarmv/rails_jwt

# Installation

Remember to...

```
$ cd rails_jwt
$ bundler
$ echo "jwt_secret: `rails secret`"    # ...copy the output of this
$ EDITOR=nano rails credentials:edit  # and paste it here.
```
Then just

```
$ rails s
```

# Testing

Test this with https://github.com/voscarmv/JWT_tester
