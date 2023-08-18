---
title: ToArray()
second_title: Aspose.Slides for C++ API Reference
description: Creates and returns an array with all shapse in it.
type: docs
weight: 287
url: /aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() method


Creates and returns an array with all shapse in it.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Return Value

Array of [IShape](../../ishape/)

## IShapeCollection::ToArray(int32_t, int32_t) method


Creates and returns an array with all shapes from the specified range in it.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | An index of a first shape to return. |
| count | **int32_t** | A number of shapes to return. |

### Return Value

Array of [IShape](../../ishape/)

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)