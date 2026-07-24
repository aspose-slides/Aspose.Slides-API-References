---
title: get_BaseJustification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt die vertikale Ausrichtung in Bezug auf den umgebenden Text an. Mögliche Werte sind oben, unten und Mitte. Standard: Mitte"
type: docs
weight: 53
url: /de/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() Methode

Specifiziert die vertikale Ausrichtung in Bezug auf den umgebenden Text. Mögliche Werte sind oben, unten und Mitte. Standard: Mitte

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Bemerkungen

Beispiel:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Siehe auch

* Aufzählung [MathVerticalAlignment](../../mathverticalalignment/)
* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)