---
title: group method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/imathelement/group/
weight: 70
---
## group(self) {#}
Az elem elhelyezése egy csoportba egy alsó kapcsos zárójel használatával

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Az elem elhelyezése egy csoportba egy csoportosító karakter, például alsó kapcsos zárójel vagy más használatával

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| character | **char** | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoportosító karakter pozíciója |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions) | A csoport karakter függőleges igazítása.<br/><br/>            Meghatározza az objektum igazítását az alapsóhoz képest.<br/><br/>            Például, ha a csoport karakter az objektum felett van, <br/><br/>            a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapsón van;<br/><br/>            ha a VerticalJustification Bottom-ra van állítva, az objektum alja az alapsón helyezkedik el |



### See Also
* class [`IMathElement`](/slides/python-net/hu/aspose.slides.mathtext/imathelement)
* class [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter)
* enumeration [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)