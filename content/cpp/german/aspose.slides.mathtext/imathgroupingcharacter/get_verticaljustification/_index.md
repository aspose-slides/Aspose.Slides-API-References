---
title: get_VerticalJustification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification von Top, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom"
type: docs
weight: 66
url: /de/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() Methode


Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Beispielweise, wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification von Top, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Hinweise


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