---
title: group method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathaccent/group/
weight: 80
---
## group(self) {#}
Umístí tento prvek do skupiny pomocí spodní složené závorky

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Umístí tento prvek do skupiny pomocí skupinového znaku, jako například spodní složená závorka nebo jiný

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Skupinový znak, například spodní složená závorka (U+23DF) nebo jakýkoli jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Pozice skupinového znaku |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání skupinového znaku.<br/><br/>            Určuje zarovnání objektu vzhledem k základní linii.<br/><br/>            Například když je skupinový znak nad objektem, <br/><br/>            Vertikální zarovnání Top znamená, že horní část objektu leží na základní linii;<br/><br/>            když je Vertikální zarovnání nastaveno na Bottom, spodní část objektu je na základní linii |



### See Also
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* třída [`MathAccent`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent)
* enumeration [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)