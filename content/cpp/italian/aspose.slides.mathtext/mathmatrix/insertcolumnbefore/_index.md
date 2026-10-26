---
title: InsertColumnBefore()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisci una nuova colonna prima di quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null.
type: docs
weight: 326
url: /it/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) metodo

Inserisci una nuova colonna prima di quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice della colonna prima della quale inserire una nuova |

## Osservazioni

Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Vedi anche

* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)