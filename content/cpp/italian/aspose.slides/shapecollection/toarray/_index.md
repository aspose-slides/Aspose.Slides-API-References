---
title: ToArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea e restituisce un array che contiene tutte le forme.
type: docs
weight: 326
url: /it/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() metodo

Crea e restituisce un array che contiene tutte le forme.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### Valore di ritorno

Un array di oggetti [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) metodo

Crea e restituisce un array che contiene tutte le forme nell'intervallo specificato.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | **int32_t** | L'indice della prima forma da restituire. |
| count | **int32_t** | Il numero di forme da restituire. |

### Valore di ritorno

Un array di oggetti [IShape](../../ishape/).

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)