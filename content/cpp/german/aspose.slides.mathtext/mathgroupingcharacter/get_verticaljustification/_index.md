---
title: get_VerticalJustification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts in Bezug auf die Grundlinie an. Zum Beispiel bedeutet, wenn das Gruppierungszeichen über dem Objekt steht, dass VerticalJustification von Top anzeigt, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom"
type: docs
weight: 66
url: /de/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() Methode

Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts in Bezug auf die Grundlinie an. Beispielsweise bedeutet bei einem über dem Objekt stehenden Gruppierungszeichen, dass die VertikalJustification von Top anzeigt, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn die VertikalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## Bemerkungen

Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Siehe auch

* Aufzählung [MathTopBotPositions](../../mathtopbotpositions/)
* Klasse [MathGroupingCharacter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)