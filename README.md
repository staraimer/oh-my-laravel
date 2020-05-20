本扩展用于 Laravel Framework 7 的一些应用层初始化

### 如何使用

```
composer require silverd/oh-my-laravel
php artisan oh-my-laravel:install
```

### 本地开发

```
cd ~/home/wwwroot/
git clone git@github.com:silverd/oh-my-laravel.git

cd ~/homw/wwwroot/sample_project
composer config repositories.silverd path ~/home/wwwroot/oh-my-laravel
composer require silverd/oh-my-laravel:dev-master -vvv
php artisan oh-my-laravel:install
```
