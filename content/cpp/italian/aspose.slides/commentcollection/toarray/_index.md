---
title: ToArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea e restituisce un array con tutti i commenti.
type: docs
weight: 105
url: /it/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() metodo

Crea e restituisce un array con tutti i commenti.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### Valore restituito

Array di [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) metodo

Crea e restituisce un array con tutti i commenti dell'intervallo specificato.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | **int32_t** | Un indice del primo commento da restituire. |
| count | **int32_t** | Un numero di commenti da restituire. |

### Valore restituito

Array di [Comment](../../comment/).

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)