---
title: ToArray()
second_title: Aspose.Slides för C++ API-referens
description: Skapar och returnerar en array med alla kommentarer.
type: docs
weight: 105
url: /sv/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() metod

Skapar och returnerar en array med alla kommentarer.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### Returvärde

Array av [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) metod

Skapar och returnerar en array med alla kommentarer från det angivna intervallet.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | **int32_t** | Index för den första kommentaren som ska returneras. |
| count | **int32_t** | Antal kommentarer att returnera. |

### Returvärde

Array av [Comment](../../comment/).

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IComment](../../icomment/)
* Klass [CommentCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)