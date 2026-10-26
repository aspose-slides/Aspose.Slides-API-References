---
title: group method
second_title: Aspose.Slides Pythonhoz a .NET API-n keresztül
description: 
type: docs
url: /hu/aspose.slides.mathtext/matharray/group/
weight: 80
---
## group(self) {#}
Elhelyezi ezt az elemet egy csoportban egy alsó kapcsos zárójel használatával

### Visszatérő érték

Új példány a [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Elhelyezi ezt az elemet egy csoportban egy csoportosító karakter, például alsó kapcsos zárójel vagy más használatával

### Visszatérő érték

Új példány a [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | Az csoport karakterének vertikális igazítása.<br/><br/>            Meghatározza az objektum igazítását az alapvonalhoz képest.<br/><br/>            Például, ha a csoport karakter a objektum fölött helyezkedik el, <br/><br/>            a Top vertikális igazítás azt jelenti, hogy az objektum teteje az alapvonalon helyezkedik el;<br/><br/>            ha a VerticalJustification értéke Bottom, akkor az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathArray`](/slides/python-net/hu/aspose.slides.mathtext/matharray)
* felsorolás [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)