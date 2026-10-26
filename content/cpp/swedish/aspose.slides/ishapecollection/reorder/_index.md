---
title: Reorder()
second_title: Aspose.Slides för C++ API-referens
description: Flyttar den angivna formen till en ny position inom formsamlingen.
type: docs
weight: 300
url: /sv/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metod

Flyttar den angivna formen till en ny position inom formsamlingen.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade målindexet där formen kommer att placeras. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Den [IShape](../../ishape/) som ska flyttas inom samlingen. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metod

Flyttar de angivna formerna inom formsamlingen och placerar dem med början vid det angivna indexet.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade målindexet där den första angivna formen kommer att placeras; efterföljande former följer i den angivna ordningen. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Ett eller flera [IShape](../../ishape/)-instanser att flytta inom samlingen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IShape](../../ishape/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)