---
title: group method
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathblock/group/
weight: 130
---
## group(self) {#}
Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával

### Visszatér

Új [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú példány



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elemet egy csoportba helyezi egy csoportosító karakter, például alsó kapcsos zárójel vagy más használatával

### Visszatér

Új [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú példány



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | Az csoport karakter függőleges igazítása.<br/><br/>            Meghatározza az objektum igazítását az alapvonalhoz képest.<br/><br/>            Például, ha a csoport karakter az objektum felett van, <br/><br/>            a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalon helyezkedik el;<br/><br/>            ha a függőleges igazítás Bottom értékre van állítva, akkor az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathBlock`](/slides/python-net/hu/aspose.slides.mathtext/mathblock)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)