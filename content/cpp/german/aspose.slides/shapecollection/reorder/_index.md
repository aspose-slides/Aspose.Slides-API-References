---
title: Reorder()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschiebt die angegebene Form an eine neue Position innerhalb der Formsammlung.
type: docs
weight: 339
url: /de/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) Methode


Verschiebt die angegebene Form an eine neue Position innerhalb der Formsammlung.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Zielindex, an dem die Form platziert wird. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Die [IShape](../../ishape/) zum Verschieben innerhalb der Sammlung. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) Methode


Verschiebt die angegebenen Formen innerhalb der Formsammlung und platziert sie beginnend am angegebenen Index.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Zielindex, an dem die erste angegebene Form platziert wird; nachfolgende Formen folgen in der angegebenen Reihenfolge. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\& | Ein oder mehrere [IShape](../../ishape/)-Instanzen zum Verschieben innerhalb der Sammlung. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IShape](../../ishape/)
* Klasse [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)