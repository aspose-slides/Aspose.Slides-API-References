---
title: ToArray()
second_title: Aspose.Slides för C++ API-referens
description: Skapar och returnerar en array som innehåller alla former.
type: docs
weight: 287
url: /sv/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() metod


Skapar och returnerar en array som innehåller alla former.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Returvärde

En array av [IShape](../../ishape/) objekt.

## IShapeCollection::ToArray(int32_t, int32_t) metod


Skapar och returnerar en array som innehåller alla former i det angivna intervallet.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | **int32_t** | Index för den första formen som ska returneras. |
| count | **int32_t** | Antalet former som ska returneras. |

### Returvärde

En array av [IShape](../../ishape/) objekt.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IShape](../../ishape/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)