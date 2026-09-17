---
title: group method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathlimit/group/
weight: 80
---
## group(self) {#}
Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer

### Rückgabewert
Neue Instanz vom Typ [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Platziert dieses Element in einer Gruppe mithilfe eines Gruppierungszeichens, z. B. einer unteren geschweiften Klammer oder eines anderen

### Rückgabewert
Neue Instanz vom Typ [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| character | **char** | Gruppierungszeichen wie UNTERE GESCHWEIFTE KLAMMER (U+23DF) oder ein anderes |
| position | [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions) | Position des Gruppierungszeichens |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions) | Vertikale Ausrichtung des Gruppierungszeichens.<br/><br/>            Gibt die Ausrichtung des Objekts relativ zur Grundlinie an.<br/><br/>            Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt liegt, <br/><br/>            VerticalJustification von Top bedeutet, dass die Oberkante des Objekts auf der Grundlinie liegt;<br/><br/>            wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterkante des Objekts auf der Grundlinie |



### Siehe auch
* Klasse [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)
* Klasse [`MathLimit`](/slides/python-net/de/aspose.slides.mathtext/mathlimit)
* Aufzählung [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)