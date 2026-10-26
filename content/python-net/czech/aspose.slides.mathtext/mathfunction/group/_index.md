---
title: group method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathfunction/group/
weight: 80
---
## group(self) {#}
Umístí tento prvek do skupiny pomocí dolního složeného závorky

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
| character | **char** | Znak pro seskupování, například BOTTOM CURLY BRACKET (U+23DF) nebo jakýkoli jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Pozice znaku pro seskupování |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání znaku skupiny.<br/><br/>            Určuje zarovnání objektu vzhledem k základní čáře.<br/><br/>            Například když je znak skupiny nad objektem, <br/><br/>            Vertikální zarovnání Top znamená, že horní část objektu leží na základní čáře;<br/><br/>            když je Vertikální zarovnání nastaveno na Bottom, spodní část objektu leží na základní čáře |



### Viz také
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* třída [`MathFunction`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction)
* enumerace [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)