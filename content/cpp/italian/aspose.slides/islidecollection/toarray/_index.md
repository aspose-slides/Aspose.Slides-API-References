---
title: ToArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea e restituisce un array contenente tutte le diapositive.
type: docs
weight: 92
url: /it/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() metodo

Crea e restituisce un array con tutte le diapositive al suo interno.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### Valore restituito

Array di [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) metodo

Crea e restituisce un array con le diapositive dell'intervallo specificato al suo interno.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | **int32_t** | Un indice della prima diapositiva da aggiungere. |
| count | **int32_t** | Un numero di diapositive da aggiungere. |

### Valore restituito

Array di [ISlide](../../islide/)

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [ISlideCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)