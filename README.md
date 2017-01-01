# odoo-docker
Docker files to build dockers based on:
* standard Odoo code
* OCB code

This work is original based on the docker from http://www.xcg-consulting.fr and available here: https://hub.docker.com/r/xcgd/odoo/

# Add volumes. For addons :
* "/opt/odoo/addons/inherited" : adapted modules from Odoo official Community version,
* "/opt/odoo/addons/external" : Community modules (OCA or others),
* "/opt/odoo/addons/nonfree" : non free modules (paid themes for example), and your own modules wich depend from nonfree module(s)
* "/opt/odoo/addons/private" : your own modules from scratch, even if they depend from other (community) modules
