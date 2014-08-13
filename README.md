#Wordpress installation via Fig and Docker

- Install Docker
- Install Fig
- `git clone` this repository and `cd` into the directory
- `fig up`

Wordpress is available at port 8000

##POW

*I really just followed the tutorial [here](https://github.com/docker/fig/blob/master/docs/wordpress.md) then git'd it for easy access*

####If you end up using this in production please do yourself a favor and add passwords and salts to your wp-config.php and your database

You can specify database password and username in your fig.yml file with environment variables.

Info on the environment variables [here](https://registry.hub.docker.com/u/orchardup/mysql/)
