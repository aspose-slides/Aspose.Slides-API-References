---
title: MathematicalText
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathematicaltext/mathematicaltext/
---

## MathematicalText() constructor

Default constructor (create String.Empty Value)
Example:
 
```php
  $mathText = new MathematicalText();
```
 

---


## MathematicalText(char) constructor

Create MathText with single symbol
Example:
 
```php
  $mathText = new MathematicalText('$');
```

### Parameters

| Parameter |Description |
| --- | --- |
| mathSymbol | single symbol |
 

---


## MathematicalText(java.lang.String) constructor

Create MathematicalText from text
Example:
 
```php
  $mathText = new MathematicalText("x+y");
```

### Parameters

| Parameter |Description |
| --- | --- |
| mathText | text value |
 

---


## MathematicalText(java.lang.String, com.aspose.slides.IPortionFormat) constructor

Create MathematicalText from text and format settings
Example:
 
```php
  $format = new PortionFormat();
  $format->setFontHeight(12);
  $mathText = new MathematicalText("x+y", $format);
```

### Parameters

| Parameter |Description |
| --- | --- |
| mathText | text value |
| portionFormat | text format settings |
 

---


