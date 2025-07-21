---
title: ToArray()
second_title: Aspose.Slides for C++ API Reference
description: Creates and returns an array that contains all shapes.
type: docs
weight: 287
url: /aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() method


Creates and returns an array that contains all shapes.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Return Value

An array of [IShape](../../ishape/) objects.

## IShapeCollection::ToArray(int32_t, int32_t) method


Creates and returns an array that contains all shapes in the specified range.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
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
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)