---
title: group method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathleftsubsuperscriptelement/group/
weight: 80
---
## group(self) {#}
Placera detta element i en grupp med en bottenklammer

### Returnerar

Ny instans av typen [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Placera detta element i en grupp med ett grupperingstecken, till exempel en bottenklammer eller ett annat

### Returnerar

Ny instans av typen [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| character | **char** | Grupperingstecken såsom BOTTOM CURLY BRACKET (U+23DF) eller någon annan |
| position | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Position av grupperingstecken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Vertikal justering av grupptecken.<br/><br/>            Anger objektets placering i förhållande till baslinjen.<br/><br/>            Till exempel, när grupptecknet är ovanför objektet, <br/><br/>            VerticalJustification of Top signifies that the top of the object falls on the baseline;<br/><br/>            when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

### Se också
* klass [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)
* klass [`MathLeftSubSuperscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/mathleftsubsuperscriptelement)
* enumeration [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)