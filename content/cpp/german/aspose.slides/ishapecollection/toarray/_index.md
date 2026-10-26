---
title: ToArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt und gibt ein Array zurück, das alle Formen enthält.
type: docs
weight: 287
url: /de/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() Methode


Erstellt und gibt ein Array zurück, das alle Formen enthält.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Rückgabewert

Ein Array von [IShape](../../ishape/) Objekten.

## IShapeCollection::ToArray(int32_t, int32_t) Methode


Erstellt und gibt ein Array zurück, das alle Formen im angegebenen Bereich enthält.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
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
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)