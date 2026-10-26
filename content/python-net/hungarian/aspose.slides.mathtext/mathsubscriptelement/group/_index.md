---
title: group method
second_title: Aspose.Slides a Python számára .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathsubscriptelement/group/
weight: 80
---
## group(self) {#}
Az elem ebbe a csoportba kerül egy alsó kapcsos zárójel használatával

### Returns
Az [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú új példány

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elem ebbe a csoportba kerül egy csoportosító karakter, például alsó kapcsos zárójel vagy más karakter használatával

### Returns
Az [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusú új példány

```python
def group(self, character, position, vertical_justification):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoport karakterének függőleges igazítása.<br/><br/>            Meghatározza az objektum igazítását az alapvonalhoz képest.<br/><br/>            Például, ha a csoport karakter az objektum felett helyezkedik el, <br/><br/>            a VerticalJustification értéke Top azt jelzi, hogy az objektum teteje az alapvonalon van;<br/><br/>            ha a VerticalJustification értéke Bottom, az objektum alja az alapvonalon van |

### See Also
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathSubscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/mathsubscriptelement)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)