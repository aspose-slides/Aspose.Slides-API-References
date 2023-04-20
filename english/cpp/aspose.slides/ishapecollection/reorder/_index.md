---
title: Reorder()
second_title: Aspose.Slides for C++ API Reference
description: Moves a shape from the collection to the specified position.
type: docs
weight: 300
url: /cpp/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) method


Moves a shape from the collection to the specified position.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Target index. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) to move. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) method


Moves shapes from the collection to the specified position. Shapes will be placed starting from index in order they appear in list.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Target index. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Shapes to move. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)