---
title: group method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathbox/group/
weight: 80
---
## group(self) {#}
Placera detta element i en grupp med en nedre klammerparentes

### Returnerar

Ny instans av typ [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Placera detta element i en grupp med ett grupperingstecken, t.ex. en nedre klammerparentes eller ett annat

### Returnerar

Ny instans av typ [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| character | **char** | Grupperingstecken såsom nedre klammerparentes (U+23DF) eller annat |
| position | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Position för grupperingstecken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Vertikal justering av grupperingstecken.<br/><br/>            Anger justeringen av objektet i förhållande till baslinjen.<br/><br/>            Till exempel, när grupperingstecknet är ovanför objektet, <br/><br/>            VertikalJustering av Top betyder att objektets topp ligger på baslinjen;<br/><br/>            när VertikalJustering är inställd på Bottom, ligger objektets botten på baslinjen |



### Se även
* klass [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)
* klass [`MathBox`](/slides/python-net/sv/aspose.slides.mathtext/mathbox)
* enumeration [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)