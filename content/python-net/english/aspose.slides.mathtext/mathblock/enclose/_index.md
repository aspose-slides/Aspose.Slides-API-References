---
title: enclose method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathblock/enclose/
weight: 100
---


## enclose {#}
Encloses a math element in parenthesis

### Returns

The math element of type [`IMathDelimiter`](/slides/python-net/aspose.slides.mathtext/imathdelimiter) which includes the parenthesis



```python
def enclose(self):
    ...
```




## enclose {#char-char}
Encloses child elements of this block in specified characters such as parenthesis or another characters as framing

### Returns

The math element of type [`IMathDelimiter`](/slides/python-net/aspose.slides.mathtext/imathdelimiter) which includes specified characters as framing



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| beginning_character | char | Beginning character (usually left bracket) |
| ending_character | char | Ending character (usually right bracket) |



## enclose {#char-char-char}
Encloses child elements of this block in specified characters such as parenthesis or another as framing
            and delimit with a separator character

### Returns

The math element of type [`IMathDelimiter`](/slides/python-net/aspose.slides.mathtext/imathdelimiter) which includes specified characters as framing and delimiter



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| beginning_character | char | Beginning character (usually left bracket) |
| ending_character | char | Ending character (usually right bracket) |
| separator_character | char | Separator character |



