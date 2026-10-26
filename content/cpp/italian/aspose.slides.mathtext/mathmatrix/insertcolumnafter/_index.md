---
title: InsertColumnAfter()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisci una nuova colonna dopo quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null.
type: docs
weight: 339
url: /it/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) metodo

Inserisci una nuova colonna dopo quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice della colonna dopo la quale inserire una nuova |
## Osservazioni



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Vedi anche

* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)