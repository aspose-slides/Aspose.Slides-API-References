---
title: get_BaseJustification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann am unteren, oberen oder mittleren Teil eines Array-Objekts ausgerichtet werden. Standardwert: Center"
type: docs
weight: 14
url: /de/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() Methode


Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann am unteren, oberen oder mittleren Teil eines Array-Objekts ausgerichtet werden. Standardwert: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
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
* Library [Aspose.Slides](../../../)