---
title: enclose
type: docs
weight: 90
url: /php-java/mathblock/enclose/
---

# enclose(char, char) method

 Encloses child elements of this block in specified characters such as parenthesis or another characters as framing
 
Example:
 
```php
  $block = new MathematicalText("x")->join("+y");
  $delimiter = $block->enclose('[', ']');
```

##  Parameters

| name | description |
| --- | --- |
| beginningCharacter | Beginning character (usually left bracket) |
| endingCharacter | Ending character (usually right bracket) |

##  Returns
The math element of type IMathDelimiter which includes specified characters as framing


# enclose(char, char, char) method

 Encloses child elements of this block in specified characters such as parenthesis or another as framing
 and delimit with a separator character
 
Example:
 
```php
  $mathBlock = new MathematicalText("x")->join("y");
  $delimiterElement = $mathBlock->enclose('{', '}', '%');
```

##  Parameters

| name | description |
| --- | --- |
| beginningCharacter | Beginning character (usually left bracket) |
| endingCharacter | Ending character (usually right bracket) |
| separatorCharacter | Separator character |

##  Returns
The math element of type IMathDelimiter which includes specified characters as framing and delimiter

