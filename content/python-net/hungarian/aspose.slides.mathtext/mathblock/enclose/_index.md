---
title: enclose method
second_title: Aspose.Slides a Python számára a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Zárójelek közé helyezi a matematikai elemet

### Returns

A [`IMathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/imathdelimiter) típusú matematikai elem, amely tartalmazza a zárójeleket



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
A blokk gyermekelemeit a megadott karakterek közé helyezi, például zárójelek vagy más karakterek keretként

### Returns

A [`IMathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/imathdelimiter) típusú matematikai elem, amely a megadott karaktereket keretként tartalmazza



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| beginning_character | **char** | Kezdő karakter (általában bal zárójel) |
| ending_character | **char** | Záró karakter (általában jobb zárójel) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
A blokk gyermekelemeit a megadott karakterek közé helyezi, például zárójelek vagy más karakterek keretként, és elválasztja egy elválasztó karakterrel
### Returns

A [`IMathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/imathdelimiter) típusú matematikai elem, amely a megadott karaktereket keretként és elválasztóként tartalmazza



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| beginning_character | **char** | Kezdő karakter (általában bal zárójel) |
| ending_character | **char** | Záró karakter (általában jobb zárójel) |
| separator_character | **char** | Elválasztó karakter |


### See Also
* osztály [`IMathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/imathdelimiter)
* osztály [`MathBlock`](/slides/python-net/hu/aspose.slides.mathtext/mathblock)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)