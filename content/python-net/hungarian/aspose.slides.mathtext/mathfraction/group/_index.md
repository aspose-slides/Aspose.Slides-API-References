---
title: group method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathfraction/group/
weight: 80
---
## group(self) {#}
Az elem elhelyezése egy csoportban alsó kapcsos zárójelezettel

### Visszatér

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elem csoportosítása egy csoportosító karakterrel, például alsó kapcsos zárójelezettel vagy más

### Visszatér

Új példány a(z) [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter) típusból



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármilyen más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | Csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | Group karakter vertikális igazítása.<br/><br/>            Megadja az objektum igazítását az alapvonalhoz képest.<br/><br/>            Például, ha a csoportkarakter az objektum felett van, <br/><br/>            a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon van;<br/><br/>            amikor a VerticalJustification Bottom-ra van állítva, akkor az objektum alja az alapvonalon van |



### Lásd még
* osztály [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* osztály [`MathFraction`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction)
* enumeráció [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)