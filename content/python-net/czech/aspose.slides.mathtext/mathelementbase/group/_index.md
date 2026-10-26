---
title: group method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathelementbase/group/
weight: 70
---
## group(self) {#}
Umístí tento prvek do skupiny pomocí spodní složené závorky

### Návratová hodnota

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Umístí tento prvek do skupiny pomocí skupinového znaku, například spodní složené závorky nebo jiného

### Návratová hodnota

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Skupinový znak, například spodní složená závorka (U+23DF) nebo jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Position of grouping character |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání skupinového znaku.<br/><br/>            Určuje zarovnání objektu vzhledem k základní linii.<br/><br/>            Například když je skupinový znak nad objektem, <br/><br/>            VerticalJustification of Top znamená, že horní část objektu leží na základní linii;<br/><br/>            když je VerticalJustification nastaven na Bottom, spodní část objektu leží na základní linii |

### Viz také
* class [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* enumeration [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)