---
title: set_MinColumnWidth()
second_title: Aspose.Slides für C++ API-Referenz
description: "Minimale Spaltenbreite in Twips (1/20 eines Punktes) Der Abstand (auch als \\u201CColumn Gap\\u201D oder \\u201CGap Width\\u201D bezeichnet) wird zur MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand (Abstand zwischen den gleichen Kanten verschiedener Spalten) zu bestimmen. Default: 0."
type: docs
weight: 92
url: /de/aspose.slides.mathtext/imathmatrix/set_mincolumnwidth/
---
## IMathMatrix::set_MinColumnWidth(uint32_t) method

Minimale Spaltenbreite in Twips (1/20 einer Punkt) Der Spaltenabstand (auch als \\u201CColumn Gap\\u201D oder \\u201CGap Width\\u201D bezeichnet) wird zur MinColumnWidth addiert, um die gesamte Matrix [Column](../../../aspose.slides/column/) Spacing (Abstand zwischen den gleichen Kanten verschiedener Spalten) zu bestimmen. Default: 0.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_MinColumnWidth(uint32_t value)=0
```

## Hinweise

Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Siehe auch

* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)