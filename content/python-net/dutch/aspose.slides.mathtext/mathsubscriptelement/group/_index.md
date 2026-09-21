---
title: group method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathsubscriptelement/group/
weight: 80
---
## group(self) {#}
Plaats dit element in een groep met een onderste accolade

### Retour

Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Plaats dit element in een groep met een groeperingskarakter zoals een onderste accolade of een ander

### Retour

Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| character | **char** | Groeperingskarakter zoals BOTTOM CURLY BRACKET (U+23DF) of een ander |
| position | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Positie van groeperingskarakter |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Verticale uitlijning van het groepskarakter.<br/><br/>            Specificeert de uitlijning van het object ten opzichte van de basislijn.<br/><br/>            Bijvoorbeeld, wanneer het groepskarakter boven het object staat, <br/><br/>            VerticalJustification of Top betekent dat de bovenkant van het object op de basislijn ligt;<br/><br/>            wanneer VerticalJustification is ingesteld op Bottom, ligt de onderkant van het object op de basislijn |

### Zie ook
* klasse [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)
* klasse [`MathSubscriptElement`](/slides/python-net/nl/aspose.slides.mathtext/mathsubscriptelement)
* enumeratie [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)