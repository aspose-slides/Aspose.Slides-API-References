---
title: group method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathmatrix/group/
weight: 110
---
## group(self) {#}
Umístí tento prvek do skupiny pomocí dolní složené závorky

### Vrací

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Umístí tento prvek do skupiny pomocí seskupovacího znaku, například dolní složené závorky nebo jiného

### Vrací

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Seskupovací znak, jako je BOTTOM CURLY BRACKET (U+23DF) nebo jakýkoli jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Pozice seskupovacího znaku |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání znakové skupiny.<br/><br/>            Specifikuje zarovnání objektu vzhledem k základní lince.<br/><br/>            Například když je znak skupiny nad objektem, <br/><br/>            VerticalJustification of Top značí, že horní část objektu leží na základní lince;<br/><br/>            když je VerticalJustification nastaveno na Bottom, spodní část objektu je na základní lince |



### Viz také
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* třída [`MathMatrix`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix)
* enumerace [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)