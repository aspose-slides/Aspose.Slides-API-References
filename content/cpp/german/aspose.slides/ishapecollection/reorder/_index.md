---
title: Reorder()
second_title: Aspose.Slides für C++ API Referenz
description: Verschiebt die angegebene Form an eine neue Position innerhalb der Formsammlung.
type: docs
weight: 300
url: /de/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) Methode

Verschiebt die angegebene Form an eine neue Position innerhalb der Formsammlung.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Zielindex, an dem die Form platziert wird. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Das [IShape](../../ishape/) zum Verschieben innerhalb der Sammlung. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) Methode

Verschiebt die angegebenen Formen innerhalb der Formsammlung und legt sie beginnend ab dem angegebenen Index ab.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Zielindex, an dem die erste angegebene Form platziert wird; nachfolgende Formen folgen in der angegebenen Reihenfolge. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Eine oder mehrere [IShape](../../ishape/)-Instanzen, die innerhalb der Sammlung verschoben werden sollen. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IShape](../../ishape/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)