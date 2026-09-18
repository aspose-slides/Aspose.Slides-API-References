---
title: group method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathlimit/group/
weight: 80
---
## group(self) {#}
Elhelyezi ezt az elemet egy csoportban egy alsó kapcsos zárójel segítségével

### Visszatérési érték

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Elhelyezi ezt az elemet egy csoportban egy csoportosító karakter használatával, például alsó kapcsos zárójellel vagy más karakterrel

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
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportkarakter függőleges igazítása.<br/><br/>            Megadja az objektum igazítását az alaponélhez képest.<br/><br/>            Például, ha a csoportkarakter az objektum felett helyezkedik el, <br/><br/>            a Top függőleges igazítás azt jelzi, hogy az objektum teteje az alapvonalon van;<br/><br/>            ha a Bottom értékre van beállítva, az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathLimit`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)