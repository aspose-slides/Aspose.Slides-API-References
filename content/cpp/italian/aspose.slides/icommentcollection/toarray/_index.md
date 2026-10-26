---
title: ToArray()
second_title: Riferimento API Aspose.Slides per C++
description: Crea e restituisce un array con tutti i commenti.
type: docs
weight: 66
url: /it/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() metodo


Crea e restituisce un array con tutti i commenti.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```


### Valore di ritorno

Array di [IComment](../../icomment/).

## ICommentCollection::ToArray(int32_t, int32_t) metodo


Crea e restituisce un array con tutti i commenti nell'intervallo specificato.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | **int32_t** | Un indice del primo commento da restituire. |
| count | **int32_t** | Il numero di commenti da restituire. |

### Valore di ritorno

Array di [IComment](../../icomment/).

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)