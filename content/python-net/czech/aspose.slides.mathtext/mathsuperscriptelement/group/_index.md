---
title: group method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathsuperscriptelement/group/
weight: 80
---
## group(self) {#}
Umístí tento prvek do skupiny pomocí spodní složené závorky

### Vrací

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Umístí tento prvek do skupiny pomocí skupinového znaku, například spodní složené závorky nebo jiného

### Vrací

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Skupinový znak, jako SPODNÍ SLOŽENÁ ZÁVORKA (U+23DF) nebo jakýkoli jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Pozice skupinového znaku |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání skupinového znaku.<br/><br/>            Určuje zarovnání objektu vzhledem k základní lince.<br/><br/>            Například když je skupinový znak nad objektem, <br/><br/>            VerticalJustification of Top znamená, že horní část objektu leží na základní lince;<br/><br/>            když je VerticalJustification nastaven na Bottom, spodní část objektu leží na základní lince |

### Viz také
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* třída [`MathSuperscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/mathsuperscriptelement)
* enumerace [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)