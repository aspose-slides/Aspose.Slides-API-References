---
title: group method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathgroupingcharacter/group/
weight: 80
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
Umístí tento prvek do skupiny pomocí skupinového znaku, například dolní složené závorky nebo jiného

### Návratová hodnota

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Skupinový znak, například DOLNÍ SLOŽENÁ ZÁVORKA (U+23DF) nebo jakýkoli jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Pozice skupinového znaku |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání skupinového znaku.<br/><br/>            Specifikuje zarovnání objektu vzhledem k základní linii.<br/><br/>            Například když je skupinový znak nad objektem, <br/><br/>            VerticalJustification hodnoty Top značí, že horní část objektu leží na základní linii;<br/><br/>            když je VerticalJustification nastaven na Bottom, spodní část objektu leží na základní linii |

### Viz také
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* třída [`MathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter)
* enumeration [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)