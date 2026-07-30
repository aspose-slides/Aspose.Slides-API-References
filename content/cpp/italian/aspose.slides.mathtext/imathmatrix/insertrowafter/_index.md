---
title: InsertRowAfter()
second_title: Riferimento API Aspose.Slides per C++
description: Inserisce una nuova riga dopo quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null.
type: docs
weight: 287
url: /it/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) metodo

Inserisce una nuova riga dopo quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rowIndex | **int32_t** | Indice della riga dopo la quale inserire una nuova |
## Osservazioni

Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Vedi anche

* Classe [IMathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)