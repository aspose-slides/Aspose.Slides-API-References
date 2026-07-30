---
title: InsertRowBefore()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce una nuova riga prima di quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null.
type: docs
weight: 274
url: /it/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) metodo

Inserisce una nuova riga prima di quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
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

* Classe [IMathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)