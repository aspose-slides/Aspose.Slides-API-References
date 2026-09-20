---
title: group method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/imathelement/group/
weight: 70
---
## group(self) {#}
Umístí tento prvek do skupiny pomocí dolní složené závorky

### Návratová hodnota
Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Umístí tento prvek do skupiny pomocí znaku pro seskupování, jako je dolní složená závorka nebo jiný

### Návratová hodnota
Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Znak pro seskupování, například dolní složená závorka (U+23DF) nebo jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Pozice znaku pro seskupování |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání znaku pro seskupování.<br/><br/>Specifikuje zarovnání objektu vzhledem k základní linii.<br/><br/>Například, když je znak pro seskupování nad objektem, <br/><br/>VerticalJustification hodnoty Top označuje, že horní část objektu leží na základní linii;<br/><br/>když je VerticalJustification nastaveno na Bottom, spodní část objektu leží na základní linii |



### Viz také
* třída [`IMathElement`](/slides/python-net/cs/aspose.slides.mathtext/imathelement)
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* enumerace [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)