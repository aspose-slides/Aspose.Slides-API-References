---
title: ToArray()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří a vrátí pole se všemi komentáři.
type: docs
weight: 105
url: /cs/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() metoda


Vytvoří a vrátí pole se všemi komentáři.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```


### Návratová hodnota

Pole typu [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) metoda


Vytvoří a vrátí pole se všemi komentáři z určeného rozsahu.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Index prvního komentáře k vrácení. |
| count | **int32_t** | Počet komentářů, které mají být vráceny. |

### Návratová hodnota

Pole typu [Comment](../../comment/).

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IComment](../../icomment/)
* Třída [CommentCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)