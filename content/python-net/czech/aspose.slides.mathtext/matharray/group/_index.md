---
title: group method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/matharray/group/
weight: 80
---
## group(self) {#}
Umístí tento prvek do skupiny pomocí dolní složené závorky

### Návratová hodnota

New instance of type [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Umístí tento prvek do skupiny pomocí znaku pro seskupení, například dolní složené závorky nebo jiného znaku

### Návratová hodnota

New instance of type [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Znak pro seskupení, například BOTTOM CURLY BRACKET (U+23DF) nebo jakýkoli jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Pozice znaku pro seskupení |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání znaku skupiny.<br/><br/>            Specifikuje zarovnání objektu vzhledem k základní lince.<br/><br/>            Například když je znak skupiny nad objektem, <br/><br/>            VerticalJustification of Top znamená, že horní část objektu leží na základní lince;<br/><br/>            když je VerticalJustification nastaveno na Bottom, spodní část objektu leží na základní lince |



### Viz také
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* třída [`MathArray`](/slides/python-net/cs/aspose.slides.mathtext/matharray)
* enumerace [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)