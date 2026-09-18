---
title: group method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathborderbox/group/
weight: 80
---
## group(self) {#}
Az elem ezt egy csoportba helyezi egy alsó kapcsos zárójel használatával

### Visszatérési érték

Új [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú példány



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elem ezt egy csoportba helyezi egy csoportosító karakter, például alsó kapcsos zárójel vagy más használatával

### Visszatérési érték

Új [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú példány



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | Az csoport karakter vertikális igazítása.<br/><br/>            Megadja az objektum igazítását az alapvonalhoz képest.<br/><br/>            Például, ha a csoport karakter az objektum felett van, <br/><br/>            a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon van;<br/><br/>            ha a VerticalJustification értéke Bottom, az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathBorderBox`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)