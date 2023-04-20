---
title: Reorder()
second_title: Aspose.Slides for C++ API Reference
description: Moves a shape from the collection to the specified position.
type: docs
weight: 339
url: /cpp/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) method


Moves a shape from the collection to the specified position.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Target index. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) to move. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) method


Moves shapes from the collection to the specified position. Shapes will be placed starting from index in order they appear in list.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
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
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)