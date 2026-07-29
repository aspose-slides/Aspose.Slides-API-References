---
title: ToArray()
second_title: Aspose.Slides för C++ API-referens
description: Skapar och returnerar en array som innehåller alla former.
type: docs
weight: 326
url: /sv/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() method

Skapar och returnerar en array som innehåller alla former.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### Returvärde

En array av [IShape](../../ishape/) objekt.

## ShapeCollection::ToArray(int32_t, int32_t) method

Skapar och returnerar en array som innehåller alla former i det angivna intervallet.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | **int32_t** | Index för den första formen som ska returneras. |
| count | **int32_t** | Antalet former som ska returneras. |

### Returvärde

En array av [IShape](../../ishape/) objekt.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IShape](../../ishape/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)