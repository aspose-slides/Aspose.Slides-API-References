---
title: group method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathdelimiter/group/
weight: 90
---
## group(self) {#}
Plaatst dit element in een groep met behulp van een onderste accolade

### Retourneert

Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Plaatst dit element in een groep met behulp van een groeperingskarakter, zoals een onderste accolade of een ander

### Retourneert

Nieuwe instantie van type [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| character | **char** | Groeperingskarakter zoals BOTTOM CURLY BRACKET (U+23DF) of een ander |
| position | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Positie van het groeperingskarakter |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions) | Vertical justification of group character.<br/><br/>            Specificeert de uitlijning van het object ten opzichte van de basislijn.<br/><br/>            Bijvoorbeeld, wanneer het groepeerteken boven het object staat, <br/><br/>            VerticalJustification of Top signifies that the top of the object falls on the baseline;<br/><br/>            when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |



### Zie ook
* klasse [`IMathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/imathgroupingcharacter)
* klasse [`MathDelimiter`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter)
* enumeratie [`MathTopBotPositions`](/slides/python-net/nl/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)