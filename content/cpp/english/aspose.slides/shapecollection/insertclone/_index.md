---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the specified shape and inserts it into the shape collection at the specified index.
type: docs
weight: 560
url: /aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) method


Creates a copy of the specified shape and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the cloned shape. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The [IShape](../../ishape/) to clone. |
| x | **float** | The x-coordinate of the cloned shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the cloned shape\\u2019s frame, in points. |
| width | **float** | The width of the cloned shape\\u2019s frame, in points. |
| height | **float** | The height of the cloned shape\\u2019s frame, in points. |

### Return Value

The newly created [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) method


Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the cloned shape. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The [IShape](../../ishape/) to clone. |
| x | **float** | The x-coordinate of the cloned shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the cloned shape\\u2019s frame, in points. |

### Return Value

The newly created [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) method


Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original\\u2019s position and size.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the cloned shape. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The [IShape](../../ishape/) to clone. |

### Return Value

The newly created [IShape](../../ishape/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)