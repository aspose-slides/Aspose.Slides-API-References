---
title: enclose method
second_title: Aspose.Slides for Python via .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Matematikai elemet zárójelek közé helyez

### Visszatérési érték

A [`IMathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/imathdelimiter) típusú matematikai elem, amely tartalmazza a zárójeleket



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Matematikai elemet a megadott karakterek közé helyez, például zárójelek vagy más karakterek keretezésként

### Visszatérési érték

Ha a `beginning_character` és az `ending_character` értéke None,
            a megfelelő tulajdonságok csak értékeket kapnak, és nem jön létre új objektum (visszatér ezzel a példánnyal).
            Ellenkező esetben új, Delimiter típusú matematikai elemet ad vissza, amely a megadott karaktereket keretezi,
            és a [`MathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter) példányát keretezi belül.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| beginning_character | **char** | Kezdő karakter (általában bal zárójel) |
| ending_character | **char** | Záró karakter (általában jobb zárójel) |



### Lásd még
* osztály [`IMathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/imathdelimiter)
* osztály [`MathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)