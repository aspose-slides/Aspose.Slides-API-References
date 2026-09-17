---
title: group method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/matharray/group/
weight: 80
---
## group(self) {#}
Platziert dieses Element in einer Gruppe mittels einer unteren geschweiften Klammer

### Rückgabe
Neue Instanz des Typs [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Platziert dieses Element in einer Gruppe mittels eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder eines anderen

### Rückgabe
Neue Instanz des Typs [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| character | **char** | Gruppierungszeichen wie BOTTOM CURLY BRACKET (U+23DF) oder ein anderes |
| position | [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions) | Position des Gruppierungszeichens |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions) | Vertikale Justierung des Gruppierungszeichens.<br/><br/>            Gibt die Ausrichtung des Objekts relativ zur Grundlinie an.<br/><br/>            Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt ist, <br/><br/>            VerticalJustification of Top bedeutet, dass die Oberseite des Objekts auf der Grundlinie liegt;<br/><br/>            wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie |

### Siehe auch
* Klasse [`IMathGroupingCharacter`](/slides/python-net/de/aspose.slides.mathtext/imathgroupingcharacter)
* Klasse [`MathArray`](/slides/python-net/de/aspose.slides.mathtext/matharray)
* Aufzählung [`MathTopBotPositions`](/slides/python-net/de/aspose.slides.mathtext/mathtopbotpositions)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)