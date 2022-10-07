---
title: MathematicalText
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathematicaltext/mathematicaltext/
---

## MathematicalText()  constructor

 Default constructor (create String.Empty Value)
 
Example:
 
```php
  $mathText = new MathematicalText();
```


---


## MathematicalText(char mathSymbol)  constructor

 Create MathText with single symbol
 
Example:
 
```php
  $mathText = new MathematicalText('$');
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| mathSymbol | char | single symbol |


---


## MathematicalText(String mathText)  constructor

 Create MathematicalText from text
 
Example:
 
```php
  $mathText = new MathematicalText("x+y");
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| mathText | String | text value |


---


## MathematicalText(String mathText, [PortionFormat](../../portionformat) portionFormat)  constructor

 Create MathematicalText from text and format settings
 
Example:
 
```php
  $format = new PortionFormat();
  $format->setFontHeight(12);
  $mathText = new MathematicalText("x+y", $format);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| mathText | String | text value |
| portionFormat | [PortionFormat](../../portionformat) | text format settings |


---


