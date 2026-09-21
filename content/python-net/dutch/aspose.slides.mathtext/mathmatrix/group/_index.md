---
title: group method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathmatrix/group/
weight: 110
---
## group(self) {#}
Plaatst dit element in een groep met behulp van een onderste accolade

### Retourwaarde
Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Plaatst dit element in een groep met behulp van een groepeeringsteken, zoals een onderste accolade of een ander teken

### Retourwaarde
Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| character | **char** | Groeperingskarakter zoals BOTTOM CURLY BRACKET (U+23DF) of een ander |
| position | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Positie van groepeeringskarakter |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Verticale uitlijning van het groepeeringskarakter.<br/><br/>            Specificeert de uitlijning van het object ten opzichte van de basislijn.<br/><br/>            Bijvoorbeeld, wanneer het groepeeringskarakter boven het object staat,<br/><br/>            VerticalJustification van Top betekent dat de bovenkant van het object op de basislijn valt;<br/><br/>            wanneer VerticalJustification is ingesteld op Bottom, ligt de onderkant van het object op de basislijn |

### Zie ook
* klasse [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)
* klasse [`MathMatrix`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix)
* enumeratie [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)