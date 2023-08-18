---
title: InsertVideoFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new video frame and inserts it to a collection at the specified index.
type: docs
weight: 222
url: /aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) method


Creates a new video frame and inserts it to a collection at the specified index.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which video frame should be inserted. |
| x | **float** | X coordinate of a new video frame. |
| y | **float** | Y coordinate of a new video frame. |
| width | **float** | Width of a new video frame. |
| height | **float** | Height of a new video frame. |
| fname | [System::String](../../../system/string/) | [Video](../../video/) file name. |

### Return Value

Created [VideoFrame](../../videoframe/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)