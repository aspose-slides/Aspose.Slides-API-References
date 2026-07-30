---
title: DeleteColumn()
second_title: Riferimento API Aspose.Slides per C++
description: Elimina la colonna specificata
type: docs
weight: 352
url: /it/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix::DeleteColumn(int32_t) metodo


Elimina la colonna specificata

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteColumn(int32_t columnIndex) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | **int32_t** | L'indice a base zero della colonna da eliminare. |
## Osservazioni



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## Vedi anche

* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)