---
title: get_MinColumnWidth()
second_title: Aspose.Slides für C++ API-Referenz
description: "Minimale Spaltenbreite in Twips (1/20 eines Punktes) Der Spaltenabstand (auch als \\u201CColumn Gap\\u201D oder \\u201CGap Width\\u201D bezeichnet) wird zur MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand (Abstand zwischen den gleichen Kanten verschiedener Spalten) zu bestimmen. Standard: 0."
type: docs
weight: 79
url: /de/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() method

Minimale Spaltenbreite in Twips (1/20 eines Punktes) Der Spaltenabstand (auch als \u201CColumn Gap\u201D oder \u201CGap Width\u201D bezeichnet) wird zur MinColumnWidth addiert, um die gesamte Matrix [Column](../../../aspose.slides/column/) Spacing (Abstand zwischen den gleichen Kanten verschiedener Spalten) zu bestimmen. Standard: 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## Bemerkungen

Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Siehe auch

* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)