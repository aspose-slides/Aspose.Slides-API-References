---
title: group method
second_title: Aspose.Slides a Pythonhoz a .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathdelimiter/group/
weight: 90
---
## group(self) {#}
A(z) elem csoportba helyezése egy alsó kapcsos zárójel segítségével

### Visszatér

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
A(z) elem csoportba helyezése egy csoportosító karakterrel, például alsó kapcsos zárójellel vagy más karakterrel

### Visszatér

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoport karakter függőleges igazítása.<br/><br/>            Meghatározza az objektum igazítását az alapon.<br/><br/>            Például, ha a csoport karakter az objektum felett van, <br/><br/>            a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalon van;<br/><br/>            ha a függőleges igazítást Bottom-re állítják, az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)