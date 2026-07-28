---
title: ToArray()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy i zwraca tablicę ze wszystkimi komentarzami.
type: docs
weight: 105
url: /pl/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() metoda

Tworzy i zwraca tablicę ze wszystkimi komentarzami.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### Wartość zwracana

Tablica [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) metoda

Tworzy i zwraca tablicę ze wszystkimi komentarzami z określonego zakresu.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks pierwszego komentarza do zwrócenia. |
| count | **int32_t** | Liczba komentarzy do zwrócenia. |

### Wartość zwracana

Tablica [Comment](../../comment/).

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)