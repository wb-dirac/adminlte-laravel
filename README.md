#AdminLTE template Laravel package
A Laravel package that switch default Laravel scaffolding/boilerplate to AdminLTE template

[![Total Downloads](https://poser.pugx.org/acacha/admin-lte-template-laravel/downloads.png)](https://packagist.org/packages/acacha/admin-lte-template-laravel)
[![Latest Stable Version](https://poser.pugx.org/acacha/admin-lte-template-laravel/v/stable.png)](https://packagist.org/packages/acacha/admin-lte-template-laravel)

#Requirements

* [Composer](https://getcomposer.org/)
* [Laravel](http://laravel.com/)

##Installation

First install Laravel ([http://laravel.com/docs/5.0/installation]). Create a new Laravel project:

<pre>
 $ laravel new laravel-with-admin-lte
 $ cd laravel-with-admin-lte
</pre>

Add admint-lte Laravel package with:

<pre>
 $ composer require "acacha/admin-lte-template-laravel:0.*"
</pre> 
 
Register ServiceProvider editing '''config/app.php''' file and adding to providers array:

<pre> 
 // Ace template provider
 'Acacha\AdminLTETemplateLaravel\Providers\AdminLTETemplateServiceProvider',
</pre>

Publish files with:

<pre>
 $ php artisan vendor:publish --force --provider="Acacha\AdminLTETemplateLaravel\Providers\AdminLTETemplateServiceProvider"
</pre> 
 
Use force to overwrite Laravel Scaffolding packages 

##AdminLTE

AdminLTE is a Free Premium Admin control Panel Theme That Is Based On Bootstrap 3.x created by Abdullah Almsaeed. See:

https://github.com/almasaeed2010/AdminLTE


## More info

http://acacha.org/mediawiki/AdminLTE#adminlte-laravel