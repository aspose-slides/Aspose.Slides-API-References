---
title: ToArray()
second_title: Riferimento API Aspose.Slides per C++
description: Crea e restituisce un array che contiene tutte le forme.
type: docs
weight: 287
url: /it/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() metodo

Crea e restituisce un array che contiene tutte le forme.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### Valore di ritorno

Un array di [IShape](../../ishape/) oggetti.

## IShapeCollection::ToArray(int32_t, int32_t) metodo

Crea e restituisce un array che contiene tutte le forme nell'intervallo specificato.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | **int32_t** | L'indice della prima forma da restituire. |
| count | **int32_t** | Il numero di forme da restituire. |

### Valore di ritorno

Un array di [IShape](../../ishape/) oggetti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)