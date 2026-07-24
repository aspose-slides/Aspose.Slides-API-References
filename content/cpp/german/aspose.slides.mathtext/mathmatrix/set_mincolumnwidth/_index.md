---
title: set_MinColumnWidth()
second_title: Aspose.Slides für C++ API-Referenz
description: "Minimale Spaltenbreite in Twips (1/20 eines Punktes) Der Abstand zwischen den Spalten (auch als \\u201CColumn Gap\\u201D oder \\u201CGap Width\\u201D bezeichnet) wird zur MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand (Abstand zwischen den gleichen Kanten verschiedener Spalten) zu bestimmen. Standard: 0."
type: docs
weight: 92
url: /de/aspose.slides.mathtext/mathmatrix/set_mincolumnwidth/
---
## MathMatrix::set_MinColumnWidth(uint32_t) Methode

Mindestspaltenbreite in Twips (1/20 eines Punktes) Der Abstand zwischen den Spalten (auch bezeichnet als \\u201CColumn Gap\\u201D oder \\u201CGap Width\\u201D) wird zur MinColumnWidth addiert, um den gesamten Matrix [Column](../../../aspose.slides/column/) Abstand (Abstand zwischen den gleichen Kanten verschiedener Spalten) zu bestimmen. Standard: 0.

```cpp
void Aspose::Slides::MathText::MathMatrix::set_MinColumnWidth(uint32_t value) override
```

## Anmerkungen

Beispiel:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Siehe Auch

* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)