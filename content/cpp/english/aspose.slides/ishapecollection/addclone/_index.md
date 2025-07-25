---
title: AddClone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the specified shape and adds it to the end of the shape collection.
type: docs
weight: 495
url: /aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method


Creates a copy of the specified shape and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The shape to clone. |
| x | **float** | The x-coordinate of the cloned shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the cloned shape\\u2019s frame, in points. |
| width | **float** | The width of the cloned shape\\u2019s frame, in points. |
| height | **float** | The height of the cloned shape\\u2019s frame, in points. |

### Return Value

The newly created [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method


Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The [IShape](../../ishape/) to clone. |
| x | **float** | The x-coordinate of the cloned shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the cloned shape\\u2019s frame, in points. |

### Return Value

The newly created [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) method


Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original\\u2019s position and size.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
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
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)