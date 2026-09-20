---
title: group method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathborderbox/group/
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
Umístí tento prvek do skupiny pomocí znaku pro seskupování, jako je dolní složená závorka nebo jiný

### Návratová hodnota

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Position of grouping character |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertical justification of group character.<br/><br/>            Specifies the alignment of the object with respect to the baseline.<br/><br/>            For example, when the group character is above the object, <br/><br/>            VerticalJustification of Top signifies that the top of the object falls on the baseline;<br/><br/>            when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

### Viz také
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* třída [`MathBorderBox`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox)
* výčet [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)