---
title: group method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathbar/group/
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
Az elemet egy csoportba helyezi egy csoportosító karakter használatával, például alsó kapcsos zárójel vagy más karakter

### Visszatér

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például ALSÓ KAPCSOS ZÁRÓJEL (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoport karakterének függőleges igazítása.<br/><br/>            Meghatározza az objektum igazítását az alapvonallal szemben.<br/><br/>            Például, ha a csoport karaktera az objektum felett van, <br/><br/>            a VerticalJustification értéke Top azt jelenti, hogy az objektum teteje az alapvonalon helyezkedik el;<br/><br/>            ha a VerticalJustification Bottom értékre van állítva, az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathBar`](/slides/python-net/hu/aspose.slides.mathtext/mathbar)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)