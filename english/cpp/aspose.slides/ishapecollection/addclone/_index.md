---
title: AddClone()
second_title: Aspose.Slides for C++ API Reference
description: Adds a copy of a specified shape to the end of the collection.
type: docs
weight: 495
url: /cpp/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method


Adds a copy of a specified shape to the end of the collection.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) to clone. |
| x | **float** | X coordinate of a new shape. |
| y | **float** | Y coordinate of a new shape. |
| width | **float** | Width of a new shape. |
| height | **float** | Height of a new shape. |

### Return Value

New shape.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method


Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) to clone. |
| x | **float** | X coordinate of a new shape. |
| y | **float** | Y coordinate of a new shape. |

### Return Value

New shape.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) method


Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) to clone. |

### Return Value

New shape.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)