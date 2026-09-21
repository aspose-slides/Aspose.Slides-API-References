---
title: group method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathphantom/group/
weight: 80
---
## group(self) {#}
Plaatst dit element in een groep met behulp van een onderliggende accolade

### Retourneert

Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Plaatst dit element in een groep met behulp van een groepeerteken, zoals een onderliggende accolade of een ander teken

### Retourneert

Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| character | **char** | Groeperend teken zoals ONDERSTE ACCOLADE (U+23DF) of een ander |
| position | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Positie van groepeerteken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Verticale uitlijning van het groepskarakter.<br/><br/>            Geeft de uitlijning van het object ten opzichte van de basislijn aan.<br/><br/>            Bijvoorbeeld, wanneer het groepskarakter boven het object staat, <br/><br/>            VerticalJustification van Top betekent dat de bovenkant van het object op de basislijn ligt;<br/><br/>            wanneer VerticalJustification is ingesteld op Bottom, ligt de onderkant van het object op de basislijn |



### Zie ook
* klasse [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)
* klasse [`MathPhantom`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom)
* enumeratie [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)