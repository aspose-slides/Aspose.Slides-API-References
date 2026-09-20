---
title: group method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathradical/group/
weight: 80
---
## group(self) {#}
Placerar det här elementet i en grupp med en nedre klammerparentes

### Returnerar

Ny instans av typ [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Placerar det här elementet i en grupp med ett grupperingstecken såsom nedre klammerparentes eller ett annat

### Returnerar

Ny instans av typ [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| character | **char** | Grupperingstecken såsom NEDRE KLAMLERANES (U+23DF) eller något annat |
| position | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Position för grupperings tecken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Vertikal justering av grupptecken.<br/><br/>            Anger objektets inriktning i förhållande till baslinjen.<br/><br/>            Till exempel, när grupptecknet är ovanför objektet, <br/><br/>            VertikalJustering av Top betyder att objektets topp ligger på baslinjen;<br/><br/>            när VertikalJustering är satt till Bottom, ligger objektets botten på baslinjen |



### Se även
* klass [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)
* klass [`MathRadical`](/slides/python-net/sv/aspose.slides.mathtext/mathradical)
* enumeration [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)