---
title: group method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathaccent/group/
weight: 80
---
## group(self) {#}
Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával

### Visszatér

Új példány a [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más

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
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoport karakterének függőleges igazítása.<br/><br/>            Meghatározza az objektum igazítását az alapvonalhoz képest.<br/><br/>            Például, ha a csoport karaktere az objektum felett van, <br/><br/>            a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalon van;<br/><br/>            ha a VerticalJustification értéke Bottom, az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathAccent`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)