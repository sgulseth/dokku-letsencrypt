# Dokku Lets encrypt plugin
*Warning, this plugin is not tested and only for available for development reasons - it's work in progress*

Because letsencrypt is required to server a server on port 80/443, you will need to manually stop nginx before running this plugin.

# Usage (ubuntu)
1. `sudo dokku plugin:install https://github.com/sgulseth/dokku-letsencrypt letsencrypt`
2. `sudo service nginx stop`
3. `dokku letsencrypt:add your-app-name example.com`
4. `sudo service nginx start`
5. Thats it

# License
This project is licensed under MIT.
See LICENSE.
