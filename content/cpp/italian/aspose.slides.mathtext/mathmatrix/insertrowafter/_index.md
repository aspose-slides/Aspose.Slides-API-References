---
title: InsertRowAfter()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce una nuova riga dopo quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null.
type: docs
weight: 300
url: /it/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) metodo


Inserisce una nuova riga dopo quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rowIndex | **int32_t** | Indice della riga dopo la quale inserire una nuova |
## Note



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Vedi anche

* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)