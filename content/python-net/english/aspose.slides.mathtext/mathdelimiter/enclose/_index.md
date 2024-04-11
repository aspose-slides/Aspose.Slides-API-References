---
title: enclose method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---


## enclose {#}
Encloses a math element in specified characters such as parenthesis or another characters as framing

### Returns

If `
beginning_character`
 and `
ending_character`
 are null, 
            corresponding properties are assigned values only and no new object is created (returns this instance).
            Otherwise, returns new math element of type Delimiter which includes specified characters as framing 
            and this instance of [`MathDelimiter`](/slides/python-net/aspose.slides.mathtext/mathdelimiter) framed inside.



```python
def enclose(self):
    ...
```




## enclose {#char-char}
Encloses a math element in specified characters such as parenthesis or another characters as framing

### Returns

If `
beginning_character`
 and `
ending_character`
 are null, 
            corresponding properties are assigned values only and no new object is created (returns this instance).
            Otherwise, returns new math element of type Delimiter which includes specified characters as framing 
            and this instance of [`MathDelimiter`](/slides/python-net/aspose.slides.mathtext/mathdelimiter) framed inside.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| beginning_character | char | Beginning character (usually left bracket) |
| ending_character | char | Ending character (usually right bracket) |



