---
title: InsertRowBefore()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce una nuova riga prima di quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null.
type: docs
weight: 287
url: /it/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) metodo


Inserisce una nuova riga prima di quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rowIndex | **int32_t** | Indice della riga prima della quale inserire una nuova |
## Osservazioni



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Vedi anche

* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)