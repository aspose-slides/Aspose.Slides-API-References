---
title: group method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathmatrix/group/
weight: 110
---
## group(self) {#}
Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer

### Rückgabe

New instance of type [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer unteren geschweiften Klammer oder einem anderen

### Rückgabe

New instance of type [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| character | **char** | Gruppierungszeichen wie UNTERE GESCHWEIFTE KLAMMER (U+23DF) oder ein anderes |
| position | [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions) | Position des Gruppierungszeichens |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions) | Vertikale Ausrichtung des Gruppierungszeichens.<br/><br/>            Gibt die Ausrichtung des Objekts in Bezug auf die Grundlinie an.<br/><br/>            Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt ist, <br/><br/>            VerticalJustification von Top bedeutet, dass die Oberseite des Objekts auf der Grundlinie liegt;<br/><br/>            wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie |



### Siehe auch
* Klasse [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)
* Klasse [`MathMatrix`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix)
* Aufzählung [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)