# apache2-wordpress-config
Configuration file for sites-available at /etc/apache2/ intended for WordPress website server. 

## installation

```bash
git clone https://github.com/rayatiga/apache2-wordpress-config.git
```

## preparing

NOTE: This is allowing override all in directory `/var/www/html/*`

Go to inside `apache2-wordpress-config` directory

```bash
cd apache2-wordpress-config/
```

## using

Move `site.conf` to `/etc/apache2/sites-available/` (apache2 site config)

```bash
mv site.conf /etc/apache2/sites-available/
```

Enable `site.conf `site config

```bash
sudo a2ensite site.conf
```
