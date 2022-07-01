---
title: enclose
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 30
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

| Name | Description |
| --- | --- |
| beginningCharacter | Beginning character (usually left bracket) |
| endingCharacter | Ending character (usually right bracket) |

### Returns
If beginningCharacter and endingCharacter are null, corresponding properties are assigned values only and no new object is created (returns this instance). Otherwise, returns new math element of type Delimiter which includes specified characters as framing and this instance of MathDelimiter framed inside.


---


