HTML Video Player
=================
HTML Video Player

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist uzdevid/yii2-video-player "*"
```

or add

```
"uzdevid/yii2-video-player": "1.0.0"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \\uzdevid\videoPlayer\VideoPlayer::widget($config); ?>```