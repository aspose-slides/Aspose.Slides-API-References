---
title: DeleteRow()
second_title: Riferimento API di Aspose.Slides per C++
description: Elimina la riga specificata
type: docs
weight: 313
url: /it/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) metodo


Elimina la riga specificata

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rowIndex | **int32_t** | L'indice basato su zero della riga da eliminare. |
## Osservazioni



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Vedi anche

* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)