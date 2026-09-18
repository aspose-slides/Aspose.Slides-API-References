---
title: group method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathfunction/group/
weight: 80
---
## group(self) {#}
Ez az elem egy csoportba helyezi egy alsó kapcsos zárójel használatával

### Returns
Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Ez az elem egy csoportba helyezi egy csoportosító karakter használatával, például alsó kapcsos zárójel vagy más

### Returns
Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például ALSSÓ KAPCSOS ZÁRJEL (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoport karakterének függőleges igazítása.<br/><br/>            Meghatározza az objektum igazítását az alapvonalhoz képest.<br/><br/>            Például, ha a csoport karaktere az objektum felett van, <br/><br/>            a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalra esik;<br/><br/>            ha a Bottom van beállítva, az objektum alja az alapvonalon van |



### See Also
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathFunction`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)