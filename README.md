# ModernBB
A refreshing and modern alternative to public forums and bulletin boards.

### Requirements
ModernBB was developed with [Laravel 4.2](https://laravel.com), so your server must have:
- PHP >= 5.4
- PHP MCrypt Extension ([How to install mcrypt on Ubuntu](http://aryo.lecture.ub.ac.id/easy-install-php-mcrypt-extension-on-ubuntu-linux/))

### Installation
To install ModernBB on your server, please make sure your server meets the requirements above.

First, clone this repository to your webroot directory:
```
cd /var/www
git clone https://github.com/zackdevine/modernbb.git
```

Then run the command to generate a new key for hashing and encryption:
```
php artisan key:generate
```

ModernBB is now installed!

### Configuration
After you install ModernBB, you must configure it for use.

Navigate to your domain where you setup ModernBB, and a configuration screen should appear. Follow the instructions through each step to fully configure your installation.

### Secure Socket Layer (SSL) Support
We highly recommend using a SSL certificate with ModernBB. Any certificate will do, but we recommend using one from a trusted certificate authority such as [Comodo](https://ssl.comodo.com/) or [Let's Encrypt](https://letsencrypt.org/).

### Troubleshooting
If you are having issues with ModernBB, please check the [documentation](https://docs.modernbb.co) and [knowledge base](https://kb.modernbb.co) to see if your problem is listed and/or solved.
