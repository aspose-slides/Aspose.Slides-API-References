---
title: group method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathgroupingcharacter/group/
weight: 80
---
## group(self) {#}
Platziert dieses Element in einer Gruppe mithilfe einer unteren geschweiften Klammer

### Returns
Neue Instanz des Typs [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Platziert dieses Element in einer Gruppe mithilfe eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einem anderen

### Returns
Neue Instanz des Typs [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| character | **char** | Gruppierungszeichen wie BOTTOM CURLY BRACKET (U+23DF) oder ein anderes |
| position | [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions) | Position des Gruppierungszeichens |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions) | Vertikale Ausrichtung des Gruppierungszeichens.<br/><br/>            Gibt die Ausrichtung des Objekts relativ zur Grundlinie an.<br/><br/>            Beispiel: Wenn das Gruppierungszeichen über dem Objekt liegt, <br/><br/>            bedeutet VerticalJustification von Top, dass die Oberkante des Objekts auf der Grundlinie liegt;<br/><br/>            wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterkante des Objekts auf der Grundlinie |

### Siehe auch
* class [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/mathgroupingcharacter)
* enumeration [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)