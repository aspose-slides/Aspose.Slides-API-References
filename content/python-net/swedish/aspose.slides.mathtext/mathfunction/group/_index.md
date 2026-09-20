---
title: group method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathfunction/group/
weight: 80
---
## group(self) {#}
Placera detta element i en grupp med en nedre krullparentes

### Returnerar

Ny instans av typen [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Placera detta element i en grupp med ett grupperings-tecken såsom nedre krullparentes eller ett annat

### Returnerar

Ny instans av typen [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| character | **char** | Grupperingstecken såsom BOTTOM CURLY BRACKET (U+23DF) eller något annat |
| position | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Placering av grupperingstecken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Vertikal justering av grupptecken.<br/><br/>            Anger objektets justering i förhållande till baslinjen.<br/><br/>            Till exempel, när grupptecknet är ovanför objektet, <br/><br/>            VerticalJustification of Top betyder att objektets topp ligger på baslinjen;<br/><br/>            när VerticalJustification är satt till Bottom, ligger objektets botten på baslinjen |



### Se även
* klass [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)
* klass [`MathFunction`](/slides/python-net/sv/aspose.slides.mathtext/mathfunction)
* enumeration [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)