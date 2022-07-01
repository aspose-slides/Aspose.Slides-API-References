---
title: MathDelimiter
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathdelimiter/mathdelimiter/
---

## MathDelimiter(com.aspose.slides.IMathElement) constructor

Initializes MathDelimiter with the specified element as single base argument
Example:
 
```php
  $element = new MathematicalText("x");
  $delimiter = new MathDelimiter($element);
```

### Parameters

| Parameter |Description |
| --- | --- |
| element | The base element to which the delimiter is applied. Can be null. |

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | Throws then element is a container for another elements, such as MathBlock. In this case, you need to call a different constructor with IEnumerable argument. |
 

---


