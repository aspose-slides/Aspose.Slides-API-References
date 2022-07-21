---
title: enclose
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 40
url: /php-java/mathdelimiter/enclose/
---

## enclose(char beginningCharacter, char endingCharacter)  method

 Encloses a math element in specified characters such as parenthesis or another characters as framing
 
Example:
 
```php
  $innerDelimiter = new MathematicalText("x")->join(",y")->enclose('{', '}');
  $outerDelimiter = $innerDelimiter->enclose('[', ']');
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |

### Returns
[MathDelimiter](../../mathdelimiter)


---


