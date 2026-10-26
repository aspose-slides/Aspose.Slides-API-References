---
title: group method
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathbox/group/
weight: 80
---
## group(self) {#}
Az elem ebben a csoportban helyezi el egy alsó kapcsos zárójelet használva

### Visszatér

Új példány a [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elem ebben a csoportban helyezi el egy csoportosító karakterrel, például alsó kapcsos zárójelel vagy más karakterrel

### Visszatér

Új példány a [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | Csoport karakterének függőleges igazítása.<br/><br/>Megadja az objektum igazítását az alapvonalhoz képest.<br/><br/>Például, ha a csoport karakter az objektum tetején van, <br/><br/>VerticalJustification Top azt jelenti, hogy az objektum teteje az alapvonalon van;<br/><br/>ha a VerticalJustification Bottom, akkor az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathBox`](/slides/python-net/hu/aspose.slides.mathtext/mathbox)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)