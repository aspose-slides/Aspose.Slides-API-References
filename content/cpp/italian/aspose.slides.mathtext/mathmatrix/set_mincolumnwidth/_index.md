---
title: set_MinColumnWidth()
second_title: Riferimento API Aspose.Slides per C++
description: "Larghezza minima della colonna in twips (1/20 di punto) La spaziatura di interruzione (anche denominata \\u201CColumn Gap\\u201D o \\u201CGap Width\\u201D) è aggiunta a MinColumnWidth per determinare la spaziatura totale Matrix Column Spacing (distanza tra gli stessi bordi di colonne diverse). Default: 0."
type: docs
weight: 92
url: /it/aspose.slides.mathtext/mathmatrix/set_mincolumnwidth/
---
## MathMatrix::set_MinColumnWidth(uint32_t) metodo

Larghezza minima della colonna in twips (1/20 di punto). La spaziatura di interruzione (anche denominata \\u201CSpazio colonna\\u201D o \\u201CLarghezza spaziatura\\u201D) viene aggiunta a MinColumnWidth per determinare la spaziatura totale Matrix [Column](../../../aspose.slides/column/) (distanza tra gli stessi bordi di colonne diverse). Default: 0.

```cpp
void Aspose::Slides::MathText::MathMatrix::set_MinColumnWidth(uint32_t value) override
```

## Osservazioni

Esempio:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Vedi anche

* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)