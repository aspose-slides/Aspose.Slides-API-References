---
title: ToArray()
second_title: Aspose.Slides för C++ API-referens
description: Skapar och returnerar en array med alla bilder i den.
type: docs
weight: 92
url: /sv/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() metod


Skapar och returnerar en array med alla bilder i den.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```


### Returvärde

Array av [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) metod


Skapar och returnerar en array med alla bilder från det angivna intervallet i den.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | **int32_t** | Ett index för den första bilden att lägga till. |
| count | **int32_t** | Ett antal bilder att lägga till. |

### Returvärde

Array av [ISlide](../../islide/)

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [ISlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)