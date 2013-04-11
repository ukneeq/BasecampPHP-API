## Synopsis
Basecamp is a web service project manager found at http://www.basecamp.com/.
Basecamp provides a REST API for developer access. Basecamp released a new version of their service with completely new APIs.
BasecampPHP-API is a PHP library that encapsulates all of the Basecamp API features into a simple to use PHP class.

See the README for details.

## Author
Fedil Grogan
http://fedil.ukneeq.com/

## Requirements
* PHP 5.3 with cURL support

## Getting Started
### Download
Download the [latest version of BasecampAPI.php](http://fedil.ukneeq.com/BasecampPHP-API/):

### Require

```php
<?php
require '/path/to/BasecampAPI.php';
?>
```

### Usage
Currently only supports private apps.
```php
<?php
  $appName = 'MyApp';
  $appContact = 'youremail@example.com';

  $basecampAccountID = '0000000';
  $basecampUsername = 'username';
  $basecampPassword = 'password';

  $bc = new Basecamp("$basecampAccountID", "$basecampUsername", "$basecampPassword", "$appName", "$appContact");

?>
```

## Function List

## Thanks
Although my attempts to search for a php library for the new basecamp API came up empty I drew inspiration from a library
for the old version [(basecamp-php-api)](http://code.google.com/p/basecamp-php-api/) and a wrapper class 
[(bdunlap / basecamp.php)](https://github.com/bdunlap/basecamp.php). I wanted to thank them for their work and give them
credit for any pieces of code that may be similar or borrowed.

## License
This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 3 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA


