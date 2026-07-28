---
title: ToArray()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza és visszaadja a tömböt, amely az összes alakzatot tartalmazza.
type: docs
weight: 287
url: /hu/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() metódus


Létrehozza és visszaadja a tömböt, amely az összes alakzatot tartalmazza.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Visszatérési érték

A [IShape](../../ishape/) objektumok tömbje.

## IShapeCollection::ToArray(int32_t, int32_t) metódus


Létrehozza és visszaadja a tömböt, amely a megadott tartományban lévő összes alakzatot tartalmazza.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | **int32_t** | Az első visszaadandó alakzat indexe. |
| count | **int32_t** | A visszaadandó alakzatok száma. |

### Visszatérési érték

A [IShape](../../ishape/) objektumok tömbje.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IShape](../../ishape/)
* Osztály [IShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)