# XDD - Xtended Dump and Debug for Laravel

`xdd` is an enhanced debugging package for Laravel, supporting global functions, facades, and logging.

## Installation

```
composer require yourvendor/xdd --dev
php artisan vendor:publish --tag=config
```

## Usage

```php
use Xdd\Facades\Xdd;

Xdd::dump($data);
Xdd::log($data);
xdd($data);
```

## Features
- Global function `xdd()`
- Facade `Xdd::dump()`
- Laravel logging support
- Pretty formatted output
