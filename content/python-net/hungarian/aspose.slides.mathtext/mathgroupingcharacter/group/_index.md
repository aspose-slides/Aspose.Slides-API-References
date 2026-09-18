---
title: group method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathgroupingcharacter/group/
weight: 80
---
## group(self) {#}
Az elem elhelyezése egy csoportban alsó kapcsos zárójel használatával

### Returns
Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elem elhelyezése egy csoportban egy csoportosító karakterrel, például alsó kapcsos zárójellel vagy más karakterrel

### Returns
Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self, character, position, vertical_justification):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például ALSÓ KAPCSOS ZÁRÓJEL (U+23DF) vagy bármelyik más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | Group karakter függőleges igazítása.<br/><br/>            Meghatározza az objektum igazítását az alapvonalhoz képest.<br/><br/>            Például, ha a csoportkarakter az objektum felett van, <br/><br/>            a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon van;<br/><br/>            ha a VerticalJustification Bottom-ra van állítva, akkor az objektum alja az alapvonalon van |

### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)