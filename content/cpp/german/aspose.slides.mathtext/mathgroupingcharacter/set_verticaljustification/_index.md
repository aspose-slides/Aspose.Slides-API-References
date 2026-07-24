---
title: set_VerticalJustification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts in Bezug auf die Grundlinie an. Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification von Top, dass die Oberkante des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterkante des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom"
type: docs
weight: 79
url: /de/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) Methode

Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts in Bezug auf die Grundlinie an. Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification von Top, dass die Oberkante des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterkante des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Bemerkungen

Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Siehe auch

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klasse [MathGroupingCharacter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)