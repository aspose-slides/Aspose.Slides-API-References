---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Inserts a copy of a specified shape to specified position of the collection.
type: docs
weight: 508
url: /cpp/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(**int32_t**, [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>, **float**, **float**, **float**, **float**) method


Inserts a copy of a specified shape to specified position of the collection.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of new shape. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) to clone. |
| x | **float** | X coordinate of a new shape. |
| y | **float** | Y coordinate of a new shape. |
| width | **float** | Width of a new shape. |
| height | **float** | Height of a new shape. |

### Return Value

Inserted shape.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IShapeCollection::InsertClone(**int32_t**, [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>, **float**, **float**) method


Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of new shape. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) to clone. |
| x | **float** | X coordinate of a new shape. |
| y | **float** | Y coordinate of a new shape. |

### Return Value

Inserted shape.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IShapeCollection::InsertClone(**int32_t**, [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>) method


Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of new shape. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) to clone. |

### Return Value

Inserted shape.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
