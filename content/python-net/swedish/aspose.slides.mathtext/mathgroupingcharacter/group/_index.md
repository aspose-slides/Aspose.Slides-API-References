---
title: group method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathgroupingcharacter/group/
weight: 80
---
## group(self) {#}
Placera detta element i en grupp med en bottenklammerparentes

### Returnerar

Ny instans av typen [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Placera detta element i en grupp med ett grupperingstecken, till exempel en bottenklammerparentes eller ett annat

### Returnerar

Ny instans av typen [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| character | **char** | Grupperingstecken, såsom BOTTOM CURLY BRACKET (U+23DF) eller någon annan |
| position | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Placering av grupperingsstecken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Vertikal justering av grupptecken.<br/><br/>            Anger objektets justering i förhållande till baslinjen.<br/><br/>            Till exempel, när grupptecknet är ovanför objektet, <br/><br/>            VerticalJustification av Top betyder att objektets topp ligger på baslinjen;<br/><br/>            när VerticalJustification är satt till Bottom, ligger objektets botten på baslinjen |



### Se även
* klass [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)
* klass [`MathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter)
* enumeration [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)