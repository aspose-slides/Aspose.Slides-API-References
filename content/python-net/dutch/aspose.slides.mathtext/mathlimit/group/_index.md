---
title: group method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathlimit/group/
weight: 80
---
## group(self) {#}
Plaatst dit element in een groep met een onderste accolade

### Retour
Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Plaatst dit element in een groep met een groeperings teken zoals een onderste accolade of een andere

### Retour
Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| character | **char** | Groeperings teken zoals BOTTOM CURLY BRACKET (U+23DF) of een ander |
| position | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Positie van het groeperings teken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Verticale uitlijning van het groeps teken.<br/><br/>            Bepaalt de uitlijning van het object ten opzichte van de basislijn.<br/><br/>            Bijvoorbeeld, wanneer het groeps teken boven het object staat, <br/><br/>            VerticalJustification van Top betekent dat de bovenkant van het object op de basislijn valt;<br/><br/>            wanneer VerticalJustification is ingesteld op Bottom, de onderkant van het object op de basislijn ligt |

### Zie ook
* class [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathLimit`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit)
* enumeration [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)