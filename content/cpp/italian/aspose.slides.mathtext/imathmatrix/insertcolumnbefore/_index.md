---
title: InsertColumnBefore()
second_title: Aspose.Slides per C++ Riferimento API
description: Inserisci una nuova colonna prima di quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null.
type: docs
weight: 313
url: /it/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) metodo


Inserisci una nuova colonna prima di quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
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

* Classe [IMathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)