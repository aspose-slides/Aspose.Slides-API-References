---
title: get_BaseJustification()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann an der Unterseite, Oberseite oder Mitte eines Array-Objekts ausgerichtet werden. Standardwert: Center"
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() Methode

Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann an der Unterseite, Oberseite oder Mitte eines Array-Objekts ausgerichtet werden. Standardwert: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
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
* Bibliothek [Aspose.Slides](../../../)