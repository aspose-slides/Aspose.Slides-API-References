---
title: set_BaseJustification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann an der Unterseite, Oberseite oder Mitte eines Array-Objekts ausgerichtet werden. Standardwert: Center"
type: docs
weight: 27
url: /de/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) Methode

Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann mit dem unteren Rand, dem oberen Rand oder der Mitte eines Array-Objekts ausgerichtet werden. Standardwert: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## Hinweise


Beispiel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Siehe auch

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klasse [IMathArray](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)