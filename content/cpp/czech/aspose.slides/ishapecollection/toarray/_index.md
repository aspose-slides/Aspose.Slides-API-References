---
title: ToArray()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří a vrátí pole, které obsahuje všechny tvary.
type: docs
weight: 287
url: /cs/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() metoda

Vytvoří a vrátí pole, které obsahuje všechny tvary.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### Návratová hodnota

Pole objektů [IShape](../../ishape/).

## IShapeCollection::ToArray(int32_t, int32_t) metoda

Vytvoří a vrátí pole, které obsahuje všechny tvary ve zvoleném rozsahu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | **int32_t** | Index prvního tvaru, který se má vrátit. |
| count | **int32_t** | Počet tvarů, které se mají vrátit. |

### Návratová hodnota

Pole objektů [IShape](../../ishape/).

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IShape](../../ishape/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)