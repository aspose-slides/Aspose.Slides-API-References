---
title: group method
second_title: Aspose.Slides for Python a .NET API hivatkozáshoz
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathphantom/group/
weight: 80
---
## group(self) {#}
Az elemet egy csoportba helyezi egy alsó kapcsos zárójel segítségével

### Visszatérési érték

Új példány a [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elemet egy csoportba helyezi egy csoportosító karakter segítségével, például alsó kapcsos zárójel vagy más

### Visszatérési érték

Új példány a [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | Vertikális igazítás a csoport karakterhez.<br/><br/>            Meghatározza az objektum igazítását az alappont (baseline) tekintetében.<br/><br/>            Például amikor a csoport karakter az objektum felett van, <br/><br/>            a VerticalJustification értéke Top azt jelzi, hogy az objektum teteje az alapponton helyezkedik el;<br/><br/>            amikor a VerticalJustification értéke Bottom van beállítva, az objektum alja az alapponton van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathPhantom`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)