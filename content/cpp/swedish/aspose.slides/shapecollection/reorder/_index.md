---
title: Reorder()
second_title: Aspose.Slides för C++ API-referens
description: Flyttar den angivna formen till en ny position inom formsamlingen.
type: docs
weight: 339
url: /sv/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metod

Flyttar den angivna formen till en ny position inom formsamlingen.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade målindex där formen kommer att placeras. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Den [IShape](../../ishape/) att flytta inom samlingen. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metod

Flyttar de angivna formerna inom formsamlingen och placerar dem med start vid det angivna indexet.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade målindex där den första angivna formen kommer att placeras; efterföljande former följer i den angivna ordningen. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Ett eller flera [IShape](../../ishape/)-instanser att flytta inom samlingen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IShape](../../ishape/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)