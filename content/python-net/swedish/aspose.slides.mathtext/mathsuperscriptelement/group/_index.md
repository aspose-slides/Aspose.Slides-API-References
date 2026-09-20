---
title: group method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathsuperscriptelement/group/
weight: 80
---
## group(self) {#}
Placera detta element i en grupp med en nedre krullparentes

### Returnerar

New instance of type [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Placera detta element i en grupp med ett grupperingstecken såsom en nedre krullparentes eller ett annat

### Returnerar

New instance of type [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| character | **char** | Grupperingstecken såsom BOTTOM CURLY BRACKET (U+23DF) eller något annat |
| position | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Position för grupperingstecken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Vertikal justering av grupptecken.<br/><br/>            Anger objektets justering i förhållande till baslinjen.<br/><br/>            Till exempel, när grupptecknet är ovanför objektet, <br/><br/>            VerticalJustification av Top betyder att objektets topp hamnar på baslinjen;<br/><br/>            när VerticalJustification är satt till Bottom, är objektets botten på baslinjen |

### Se även
* klass [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)
* klass [`MathSuperscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement)
* enumeration [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)