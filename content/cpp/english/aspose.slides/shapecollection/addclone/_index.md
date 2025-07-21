---
title: AddClone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the specified shape and adds it to the end of the shape collection.
type: docs
weight: 547
url: /aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method


Creates a copy of the specified shape and adds it to the end of the shape collection.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The shape to clone. |
| x | **float** | The x-coordinate of the new shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the new shape\\u2019s frame, in points. |
| width | **float** | The width of the new shape\\u2019s frame, in points. |
| height | **float** | The height of the new shape\\u2019s frame, in points. |

### Return Value

The newly created [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method


Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The shape to clone. |
| x | **float** | The x-coordinate of the new shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the new shape\\u2019s frame, in points. |

### Return Value

The newly created [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method


Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original\\u2019s position and size.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The [IShape](../../ishape/) to clone. |

### Return Value

The newly created [IShape](../../ishape/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)