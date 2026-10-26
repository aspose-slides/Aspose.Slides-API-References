---
title: ToArray()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří a vrátí pole, které obsahuje všechny tvary.
type: docs
weight: 326
url: /cs/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() metoda

Vytvoří a vrátí pole, které obsahuje všechny tvary.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### Návratová hodnota

Pole objektů [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) metoda

Vytvoří a vrátí pole, které obsahuje všechny tvary ve specifikovaném rozsahu.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | **int32_t** | Index prvního tvaru, který má být vrácen. |
| count | **int32_t** | Počet tvarů, které mají být vráceny. |

### Návratová hodnota

Pole objektů [IShape](../../ishape/).

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IShape](../../ishape/)
* třída [ShapeCollection](../)
* jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)