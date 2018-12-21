# New RCC Template based on Drupal core 8.6.4
New RCC Template based on Bootstrap Mint

## Installing The Theme
- `git clone git@github.com:rcc-uchicago/new-rcc-template-drupal8.git` to your domain directory i.e. www
- Import file "Database Backup/new-rcc-template.sql" to phpMyadmin (http://localhost/phpmyadmin/ of http://your_website.com/phpmyadmin)
- Edit file "sites/default/settings.php" line # 771 - 780 with proper database name and credentials:

```html
$databases['default']['default'] = array (
  'database' => 'new-rcc-template',
  'username' => 'root',
  'password' => '',
  'prefix' => '',
  'host' => 'localhost',
  'port' => '3306',
  'namespace' => 'Drupal\\Core\\Database\\Driver\\mysql',
  'driver' => 'mysql',
);
```
- Done! Now, go to your website. http://localhost/new-rcc-template-drupal8

## For admin access:
- http://localhost/new-rcc-template-drupal8/user
### Username and Password: 
- User: "admin"
- Password: "password123"
