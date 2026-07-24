---
title: get_MinColumnWidth()
second_title: Aspose.Slides für C++ API-Referenz
description: "Minimale Spaltenbreite in Twips (1/20 eines Punktes) Der Abstand (auch bezeichnet als \\u201CColumn Gap\\u201D oder \\u201CGap Width\\u201D) wird zur MinColumnWidth hinzugefügt, um den gesamten Matrix-Spaltenabstand (Abstand zwischen denselben Kanten verschiedener Spalten) zu bestimmen. Standard: 0."
type: docs
weight: 79
url: /de/aspose.slides.mathtext/mathmatrix/get_mincolumnwidth/
---
## MathMatrix::get_MinColumnWidth() Methode

Minimale Spaltenbreite in Twips (1/20 eines Punktes) Der Abstand (auch bezeichnet als \\u201CColumn Gap\\u201D oder \\u201CGap Width\\u201D) wird zur MinColumnWidth hinzugefügt, um die gesamte Matrix [Column](../../../aspose.slides/column/) Abstand (Abstand zwischen denselben Kanten verschiedener Spalten) zu bestimmen. Default: 0.

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_MinColumnWidth() override
```

## Anmerkungen

Beispiel:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Siehe auch

* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)