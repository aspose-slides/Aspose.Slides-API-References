---
title: set_VerticalJustification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification von Top, dass die Oberkante des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterkante des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom"
type: docs
weight: 79
url: /de/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) Methode


Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification von Top, dass die Oberkante des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterkante des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Anmerkungen


Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Siehe auch

* Aufzählung [MathTopBotPositions](../../mathtopbotpositions/)
* Klasse [IMathGroupingCharacter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)