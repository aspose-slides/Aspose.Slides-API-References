---
title: group method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathematicaltext/group/
weight: 80
---
## group(self) {#}
Placera detta element i en grupp med en nedre klammerparentes

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Placera detta element i en grupp med ett grupperingstecken, t.ex. en nedre klammerparentes eller ett annat

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | Grupperingssymbol såsom BOTTOM CURLY BRACKET (U+23DF) eller någon annan |
| position | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Position för grupperingstecken |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions) | Vertikal justering av grupptecken.<br/><br/>            Anger objektets inriktning i förhållande till baslinjen.<br/><br/>            Till exempel, när grupptecknet är ovanför objektet, <br/><br/>            VerticalJustification of Top betyder att objektets topp ligger på baslinjen;<br/><br/>            när VerticalJustification är satt till Bottom, ligger objektets botten på baslinjen |



### Se även
* klass [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter)
* klass [`MathematicalText`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext)
* enumeration [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)