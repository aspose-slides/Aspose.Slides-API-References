---
title: MathematicalText
type: docs
weight: 10
url: /php-java/mathematicaltext/mathematicaltext/
---

# MathematicalText() constructor

 Default constructor (create String.Empty Value)
 
Example:
 
```php
  $mathText = new MathematicalText();
```


# MathematicalText(char) constructor

 Create MathText with single symbol
 
Example:
 
```php
  $mathText = new MathematicalText('$');
```

##  Parameters

| name | description |
| --- | --- |
| mathSymbol | single symbol |


# MathematicalText(java.lang.String) constructor

 Create MathematicalText from text
 
Example:
 
```php
  $mathText = new MathematicalText("x+y");
```

##  Parameters

| name | description |
| --- | --- |
| mathText | text value |


# MathematicalText(java.lang.String, com.aspose.slides.IPortionFormat) constructor

 Create MathematicalText from text and format settings
 
Example:
 
```php
  $format = new PortionFormat();
  $format->setFontHeight(12);
  $mathText = new MathematicalText("x+y", $format);
```

##  Parameters

| name | description |
| --- | --- |
| mathText | text value |
| portionFormat | text format settings |

