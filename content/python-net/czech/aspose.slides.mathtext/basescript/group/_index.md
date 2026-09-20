---
title: group method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/basescript/group/
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
Umístí tento prvek do skupiny pomocí znaků pro skupinování, jako je dolní složená závorka nebo jiný znak

### Návratová hodnota

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Znak pro skupinování, například dolní složená závorka (U+23DF) nebo jakýkoli jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Pozice znaku pro skupinování |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání znaku skupiny.<br/><br/>            Určuje zarovnání objektu vzhledem k základní linii.<br/><br/>            Například když je znak skupiny nad objektem, <br/><br/>            VerticalJustification hodnoty Top znamená, že horní část objektu leží na základní linii;<br/><br/>            když je VerticalJustification nastaveno na Bottom, spodní část objektu leží na základní lince |



### Viz také
* třída [`BaseScript`](/slides/python-net/cs/aspose.slides.mathtext/basescript)
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* výčet [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)