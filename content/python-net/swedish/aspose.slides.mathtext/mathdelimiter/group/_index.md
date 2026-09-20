---
title: group method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathdelimiter/group/
weight: 90
---
## group(self) {#}
Placerar detta element i en grupp med en nedre krullparentes

### Returnerar

New instance of type [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Placerar detta element i en grupp med en grupperingskaraktär såsom en nedre krullparentes eller en annan

### Returnerar

New instance of type [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| character | **char** | Grupperingskaraktär såsom NEDRE KRULLPARENTES (U+23DF) eller någon annan |
| position | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Position av grupperingskaraktär |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Vertikal justering av gruppkaraktär.<br/><br/> Anger objektets justering i förhållande till baslinjen.<br/><br/> Till exempel, när gruppkaraktären är ovanför objektet, <br/><br/> VerticalJustification av Top betyder att objektets topp ligger på baslinjen;<br/><br/> när VerticalJustification är inställd på Bottom, ligger objektets botten på baslinjen |

### Se även
* klass [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)
* klass [`MathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter)
* enumeration [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)