---
title: group method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathradical/group/
weight: 80
---
## group(self) {#}
Platziert dieses Element in einer Gruppe unter Verwendung einer unteren geschweiften Klammer

### Rückgabewert

Neue Instanz vom Typ [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Platziert dieses Element in einer Gruppe mithilfe eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einem anderen

### Rückgabewert

Neue Instanz vom Typ [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| character | **char** | Gruppierungszeichen wie die UNTERE GESCHWEIFTE KLAMMER (U+23DF) oder ein anderes |
| position | [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions) | Position des Gruppierungszeichens |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions) | Vertikale Ausrichtung des Gruppierungszeichens.<br/><br/>            Gibt die Ausrichtung des Objekts in Bezug auf die Grundlinie an.<br/><br/>            Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt liegt, <br/><br/>            bedeutet VerticalJustification von Top, dass die Oberseite des Objekts auf der Grundlinie liegt;<br/><br/>            wenn VerticalJustification auf Bottom gesetzt ist, befindet sich die Unterseite des Objekts auf der Grundlinie |



### Siehe auch
* Klasse [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)
* Klasse [`MathRadical`](/slides/python-net/de/aspose.slides.mathtext/mathradical)
* Aufzählung [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)