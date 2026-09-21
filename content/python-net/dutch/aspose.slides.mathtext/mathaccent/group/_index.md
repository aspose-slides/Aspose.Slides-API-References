---
title: group method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathaccent/group/
weight: 80
---
## group(self) {#}
Plaats dit element in een groep met behulp van een bottom curly bracket

### Retourwaarde
Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Plaats dit element in een groep met behulp van een groepeerteken zoals bottom curly bracket of een ander

### Retourwaarde
Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| character | **char** | Groeperend teken zoals BOTTOM CURLY BRACKET (U+23DF) of elk ander |
| position | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Positie van het groepeerteken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Vertical justification van het groepeerteken.<br/><br/>            Geeft de uitlijning van het object ten opzichte van de basislijn aan.<br/><br/>            Bijvoorbeeld, wanneer het groepeerteken zich boven het object bevindt, <br/><br/>            VerticalJustification van Top betekent dat de bovenkant van het object op de basislijn valt;<br/><br/>            wanneer VerticalJustification is ingesteld op Bottom, bevindt de onderkant van het object zich op de basislijn |

### Zie ook
* klasse [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)
* klasse [`MathAccent`](/slides/python-net/nl/aspose.slides.mathtext/mathaccent)
* enumeratie [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)