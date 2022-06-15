---
title: MathematicalText
type: docs
weight: 0
url: /php-java/mathematicaltext/
---

# MathematicalText class

 Mathematical text
 
Example:
 
```php
  $mathText = new MathematicalText("x+y");
```

## Constructors

| name | description |
| --- | --- |
| [MathematicalText](/slides/php-java/mathematicaltext/mathematicaltext/)() | Default constructor (create String.Empty Value) |
| [MathematicalText](/slides/php-java/mathematicaltext/mathematicaltext/)(char) | Create MathText with single symbol |
| [MathematicalText](/slides/php-java/mathematicaltext/mathematicaltext/)(String) | Create MathematicalText from text |
| [MathematicalText](/slides/php-java/mathematicaltext/mathematicaltext/)(String, IPortionFormat) | Create MathematicalText from text and format settings |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getChildren](/slides/php-java/mathematicaltext/getchildren/)() | IMathElement | Get children elements |
| [getFormat](/slides/php-java/mathematicaltext/getformat/)() | IPortionFormat | Text formatting properties |
| [getValue](/slides/php-java/mathematicaltext/getvalue/)() | String | Text value |
| [setValue](/slides/php-java/mathematicaltext/setvalue/)(String) | void | Text value |
