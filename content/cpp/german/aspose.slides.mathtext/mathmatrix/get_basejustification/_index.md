---
title: get_BaseJustification()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt die vertikale Ausrichtung im Verhältnis zum umgebenden Text an. Mögliche Werte sind top, bottom und center. Standard: Center"
type: docs
weight: 53
url: /de/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() Methode

Gibt die vertikale Ausrichtung im Verhältnis zum umgebenden Text an. Mögliche Werte sind top, bottom und center. Standard: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## Anmerkungen

Beispiel:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Siehe auch

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)