---
title: ToArray()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt und gibt ein Array zurück, das alle Formen enthält.
type: docs
weight: 326
url: /de/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() method

Erstellt und gibt ein Array zurück, das alle Formen enthält.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### Rückgabewert

Ein Array von [IShape](../../ishape/) Objekten.

## ShapeCollection::ToArray(int32_t, int32_t) method

Erstellt und gibt ein Array zurück, das alle Formen im angegebenen Bereich enthält.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | **int32_t** | Der Index der ersten zurückzugebenden Form. |
| count | **int32_t** | Die Anzahl der zurückzugebenden Formen. |

### Rückgabewert

Ein Array von [IShape](../../ishape/) Objekten.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)