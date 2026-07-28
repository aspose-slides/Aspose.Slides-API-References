---
title: ToArray()
second_title: Aspose.Slides C++ API Referenciája
description: Létrehozza és visszaad egy tömböt, amely az összes alakzatot tartalmazza.
type: docs
weight: 326
url: /hu/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() metódus


Létrehoz és visszaad egy tömböt, amely az összes alakzatot tartalmazza.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```


### Visszatérési érték

Egy [IShape](../../ishape/) objektumok tömbje.

## ShapeCollection::ToArray(int32_t, int32_t) metódus


Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes alakzatot tartalmazza.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | **int32_t** | Az első visszaadandó alakzat indexe. |
| count | **int32_t** | A visszaadandó alakzatok száma. |

### Visszatérési érték

Egy [IShape](../../ishape/) objektumok tömbje.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IShape](../../ishape/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)