---
title: get_MinColumnWidth()
second_title: Riferimento API di Aspose.Slides per C++
description: "Larghezza minima della colonna in twip (1/20 di punto) Lo spazio intercolonna (anche indicato come \\u201CColumn Gap\\u201D o \\u201CGap Width\\u201D) viene aggiunto a MinColumnWidth per determinare la spaziatura totale della Matrice Colonna (distanza tra gli stessi bordi di colonne diverse). Default: 0."
type: docs
weight: 79
url: /it/aspose.slides.mathtext/mathmatrix/get_mincolumnwidth/
---
## MathMatrix::get_MinColumnWidth() metodo


Larghezza minima della colonna in twip (1/20 di punto). Lo spazio intercolonna (anche indicato come “Column Gap” o “Gap Width”) viene aggiunto a MinColumnWidth per determinare la spaziatura totale della Matrice [Column](../../../aspose.slides/column/) (distanza tra gli stessi bordi di colonne diverse). Default: 0.

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_MinColumnWidth() override
```

## Osservazioni


Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Vedi anche

* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)