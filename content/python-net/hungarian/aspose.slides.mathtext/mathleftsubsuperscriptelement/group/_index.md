---
title: group method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozásán keresztül
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathleftsubsuperscriptelement/group/
weight: 80
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
Az elemet egy csoportba helyezi egy csoportosító karakterrel, például egy alsó kapcsos zárójellel vagy másvalamivel

### Visszatér

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoport karakter függőleges igazítása.<br/><br/>            Megadja az objektum igazítását az alapsorhoz képest.<br/><br/>            Például, ha a csoport karakter az objektum felett van, <br/><br/>            a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapsoron van;<br/><br/>            ha a függőleges igazítás Bottom-ra van állítva, az objektum alja az alapsoron helyezkedik el |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathLeftSubSuperscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/mathleftsubsuperscriptelement)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)