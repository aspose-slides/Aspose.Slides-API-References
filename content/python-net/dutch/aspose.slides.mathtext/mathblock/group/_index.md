---
title: group method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathblock/group/
weight: 130
---
## group(self) {#}
Plaats dit element in een groep met behulp van een onderste accoladesluiter

### Retour
Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Plaats dit element in een groep met behulp van een groepskarakter zoals een onderste accoladesluiter of een ander

### Retour
Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | Groepskarakter zoals BOTTOM CURLY BRACKET (U+23DF) of een ander |
| position | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Positie van het groepskarakter |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Verticale uitlijning van groepskarakter.<br/><br/>            Specificeert de uitlijning van het object ten opzichte van de basislijn.<br/><br/>            Bijvoorbeeld, wanneer het groepskarakter zich boven het object bevindt, <br/><br/>            VerticalJustification van Top betekent dat de bovenkant van het object op de basislijn valt;<br/><br/>            wanneer VerticalJustification is ingesteld op Bottom, bevindt de onderkant van het object zich op de basislijn |

### Zie ook
* klasse [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)
* klasse [`MathBlock`](/slides/python-net/nl/aspose.slides.mathtext/mathblock)
* enumeratie [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)