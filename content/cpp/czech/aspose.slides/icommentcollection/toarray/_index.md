---
title: ToArray()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří a vrátí pole se všemi komentáři.
type: docs
weight: 66
url: /cs/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() metoda

Vytvoří a vrátí pole se všemi komentáři.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```

### Návratová hodnota

Pole [IComment](../../icomment/).

## ICommentCollection::ToArray(int32_t, int32_t) metoda

Vytvoří a vrátí pole se všemi komentáři ze zadaného rozsahu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | **int32_t** | Index prvního komentáře, který se má vrátit. |
| count | **int32_t** | Počet komentářů, které se mají vrátit. |

### Návratová hodnota

Pole [IComment](../../icomment/).

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IComment](../../icomment/)
* Třída [ICommentCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)