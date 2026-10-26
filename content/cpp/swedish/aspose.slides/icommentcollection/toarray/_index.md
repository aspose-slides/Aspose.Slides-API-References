---
title: ToArray()
second_title: Aspose.Slides för C++ API-referens
description: Skapar och returnerar en array med alla kommentarer.
type: docs
weight: 66
url: /sv/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() metod

Skapar och returnerar en array med alla kommentarer.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```

### Returvärde

Array av [IComment](../../icomment/).

## ICommentCollection::ToArray(int32_t, int32_t) metod

Skapar och returnerar en array med alla kommentarer från det angivna intervallet.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | **int32_t** | Ett index för den första kommentaren att returnera. |
| count | **int32_t** | Ett antal kommentarer att returnera. |

### Returvärde

Array av [IComment](../../icomment/).

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IComment](../../icomment/)
* Klass [ICommentCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)