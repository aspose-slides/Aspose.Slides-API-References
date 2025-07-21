---
title: ToArray()
second_title: Aspose.Slides for C++ API Reference
description: Creates and returns an array that contains all shapes.
type: docs
weight: 326
url: /aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() method


Creates and returns an array that contains all shapes.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```


### Return Value

An array of [IShape](../../ishape/) objects.

## ShapeCollection::ToArray(int32_t, int32_t) method


Creates and returns an array that contains all shapes in the specified range.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | The index of the first shape to return. |
| count | **int32_t** | The number of shapes to return. |

### Return Value

An array of [IShape](../../ishape/) objects.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)