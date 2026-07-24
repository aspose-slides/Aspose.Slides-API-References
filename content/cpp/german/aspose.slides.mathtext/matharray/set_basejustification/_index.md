---
title: set_BaseJustification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann am unteren, oberen oder mittleren Teil eines Array-Objekts ausgerichtet werden. Standardwert: Center"
type: docs
weight: 27
url: /de/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) Methode

Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann mit dem unteren, oberen oder mittleren Teil eines Array-Objekts ausgerichtet werden. Standardwert: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## Hinweise

Beispiel:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Siehe auch

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klasse [MathArray](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)