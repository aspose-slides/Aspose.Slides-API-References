---
title: group method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathradical/group/
weight: 80
---
## group(self) {#}
Az elem elhelyezése egy csoportba egy alsó kapcsos zárójellel

### Visszatérési érték

New instance of type [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elem elhelyezése egy csoportban egy csoportosító karakterrel, például alsó kapcsos zárójellel vagy másval

### Visszatérési érték

New instance of type [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportjellel kapcsolatos függőleges igazítás.<br/><br/>            Megadja az objektum igazítását az alapon.<br/><br/>            Például, ha a csoportjel az objektum felett helyezkedik el, <br/><br/>            a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalra esik;<br/><br/>            ha a VerticalJustification értéke Bottom, az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathRadical`](/slides/python-net/hu/aspose.slides.mathtext/mathradical)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)