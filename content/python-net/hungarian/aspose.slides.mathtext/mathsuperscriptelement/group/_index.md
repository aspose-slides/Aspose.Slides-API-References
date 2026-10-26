---
title: group method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathsuperscriptelement/group/
weight: 80
---
## group(self) {#}
Elhelyezi ezt az elemet egy csoportban egy alsó kapcsos zárójel használatával

### Visszatérési érték

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Elhelyezi ezt az elemet egy csoportban egy csoportosító karakter használatával, például alsó kapcsos zárójel vagy más

### Visszatérési érték

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például alsó kapcsos zárójel (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportkarakter függőleges igazítása.<br/><br/>            Megadja az objektum igazítását az alapon belül.<br/><br/>            Például, ha a csoportkarakter az objektum felett van, <br/><br/>            A Top függőleges igazítása azt jelenti, hogy az objektum teteje az alapon helyezkedik el;<br/><br/>            ha a VerticalJustification értéke Bottom, az objektum alja az alapon helyezkedik el |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathSuperscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)