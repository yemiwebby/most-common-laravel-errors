<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:


## List of all common errors and Exceptions in Laravel

Personally, I have come across a lot of errors when developing applications with Laravel. Most of the errors reoccurs during development. So I thought of the need to create this repo.


## Common Errors / Exception

1. Class "User" not found

> Write the use Full\Namespace\To\Class; 
  (Example use App\User;) at the top of the file (also known as import class in PHPStorm when you click on the yellow light bulb).


2. Class 'App\Http\Controllers\Auth

> include `use Illuminate\Support\Facades\Auth` at the top of class.



## Contributing 
Please feel free to fork this package and document any error encounter during development or on the live server with applications built with Laravel. 

See [Contribution Guide](https://github.com/yemiwebby/most-common-laravel-errors/blob/master/CONTRIBUTING.md) for more info.

## Credits

* [RUFFLES](https://laracasts.com/discuss/channels/tips/a-list-of-most-common-laravel-errors-exceptions)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
