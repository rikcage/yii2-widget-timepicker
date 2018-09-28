yii2-widget-timepicker
======================

it's a clone from https://github.com/kartik-v/yii2-widget-timepicker with a difference unlimited clock

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

To install, either run

```
$ php composer.phar require kartik-v/yii2-widget-timepicker "*"
```

or add

```
"kartik-v/yii2-widget-timepicker": "*"
```

to the ```require``` section of your `composer.json` file.

## Usage

```php
use kartik\time\TimePicker;

// usage without model
echo '<label>Start Time</label>';
echo TimePicker::widget([
	'name' => 'start_time', 
	'value' => '11:24 AM',
	'pluginOptions' => [
		'showSeconds' => true
	]
]);
```
