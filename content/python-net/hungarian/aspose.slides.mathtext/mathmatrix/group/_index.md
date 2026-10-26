---
title: group method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathmatrix/group/
weight: 110
---
## group(self) {#}
Az elem elhelyezése egy csoportba egy alsó kapcsos zárójel használatával

### Visszatérési érték

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elem elhelyezése egy csoportba egy csoportosító karakterrel, például alsó kapcsos záróval vagy másval

### Visszatérési érték

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoport karakterének függőleges igazítása.<br/><br/>            Megadja az objektum igazítását az alapvonalhoz képest.<br/><br/>            Például, ha a csoport karaktere az objektum felett van, <br/><br/>            a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon van;<br/><br/>            ha a VerticalJustification értéke Bottom, akkor az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathMatrix`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix)
* felsorolás [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)