---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Inserts a copy of a specified shape to specified position of the collection.
type: docs
weight: 560
url: /aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) method


Inserts a copy of a specified shape to specified position of the collection.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
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

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) method


Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
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

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) method


Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
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
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)