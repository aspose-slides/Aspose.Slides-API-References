---
title: get_MinColumnWidth()
second_title: Riferimento API di Aspose.Slides per C++
description: "Larghezza minima della colonna in twip (1/20 di punto) La spaziatura del gap (nota anche come \\u201CColumn Gap\\u201D o \\u201CGap Width\\u201D) viene aggiunta al MinColumnWidth per determinare la spaziatura totale della Matrix Column Spacing (distanza tra gli stessi bordi di colonne diverse). Predefinito: 0."
type: docs
weight: 79
url: /it/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() metodo

Larghezza minima della colonna in twip (1/20 di punto) Lo spazio di separazione (anche chiamato \\u201CColumn Gap\\u201D o \\u201CGap Width\\u201D) viene aggiunto al MinColumnWidth per determinare la spaziatura totale della Matrix [Column](../../../aspose.slides/column/) Spacing (distanza tra gli stessi bordi di colonne diverse). Predefinito: 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## Osservazioni


Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Vedi anche

* Classe [IMathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)