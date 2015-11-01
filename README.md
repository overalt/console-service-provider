Console Service Provider
------------------------

To see the complete documentation, check out [Console](http://symfony.com/doc/current/components/console/introduction.html)

Install
-------
```bash
composer require sergiors/console-service-provider
```

How to use
----------
```php
use Silex\Application;
use Sergiors\Silex\Provider\ConsoleServiceProvider;

$app = new Application();
$app->register(new ConsoleServiceProvider());
$app->boot();
$app['console']->run();
```
