---
title: group method
second_title: Aspose.Slides for Python via .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.mathtext/basescript/group/
weight: 70
---
## group(self) {#}
Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával

### Visszatér

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójellel vagy más

### Visszatér

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármilyen más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoport karakterének függőleges igazítása.<br/><br/>            Meghatározza az objektum igazítását az alapvonalhoz képest.<br/><br/>            Például ha a csoport karakter az objektum felett van, <br/><br/>            A Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon van;<br/><br/>            ha a VerticalJustification értéke Bottom, akkor az objektum alja az alapvonalon van |



### Lásd még
* osztály [`BaseScript`](/slides/python-net/hu/aspose.slides.mathtext/basescript)
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)