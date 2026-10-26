---
title: group method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathbar/group/
weight: 80
---
## group(self) {#}
Placerar detta element i en grupp med hjälp av en nedre krullparentes

### Returnerar

Ny instans av typ [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Placerar detta element i en grupp med hjälp av ett grupperingstecken såsom nedre krullparentes eller ett annat

### Returnerar

Ny instans av typ [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| character | **char** | Grupperingstecken såsom NEDRE KRULLPARENTES (U+23DF) eller någon annan |
| position | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Position för grupperingstecken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Vertikal justering av grupperingstecken.<br/><br/>            Anger justeringen av objektet i förhållande till baslinjen.<br/><br/>            Till exempel, när grupperingstecknet är ovanför objektet, <br/><br/>            VerticalJustification of Top betyder att objektets topp faller på baslinjen;<br/><br/>            när VerticalJustification är satt till Bottom, ligger objektets botten på baslinjen |



### Se även
* klass [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)
* klass [`MathBar`](/slides/python-net/sv/aspose.slides.mathtext/mathbar)
* enumeration [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)