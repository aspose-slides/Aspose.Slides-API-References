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


### Examples

Example:


## enclose {#systemchar-systemchar}
Encloses child elements of this block in specified characters such as parenthesis or another characters as framing

### Returns

The math element of type [`IMathDelimiter`](/slides/python-net/aspose.slides.mathtext/imathdelimiter) which includes specified characters as framing



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| beginning_character | **System.Char** | Beginning character (usually left bracket) |
| ending_character | **System.Char** | Ending character (usually right bracket) |

### Examples

Example:


## enclose {#systemchar-systemchar-systemchar}
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
| beginning_character | **System.Char** | Beginning character (usually left bracket) |
| ending_character | **System.Char** | Ending character (usually right bracket) |
| separator_character | **System.Char** | Separator character |

### Examples

Example:



### See Also
* class [`IMathDelimiter`](/slides/python-net/aspose.slides.mathtext/imathdelimiter)
* class [`MathBlock`](/slides/python-net/aspose.slides.mathtext/mathblock)
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

