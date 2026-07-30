---
title: InsertColumnAfter()
second_title: Riferimento API Aspose.Slides per C++
description: Inserisce una nuova colonna dopo quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null.
type: docs
weight: 326
url: /it/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) metodo

Inserisce una nuova colonna dopo quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
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

* Classe [IMathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)