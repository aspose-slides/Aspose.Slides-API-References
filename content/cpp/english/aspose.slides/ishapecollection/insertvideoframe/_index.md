---
title: InsertVideoFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new video frame and inserts it into the shape collection at the specified index.
type: docs
weight: 183
url: /aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) method


Creates a new video frame and inserts it into the shape collection at the specified index.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the video frame. |
| x | **float** | The x-coordinate of the new video frame, in points. |
| y | **float** | The y-coordinate of the new video frame, in points. |
| width | **float** | The width of the new video frame, in points. |
| height | **float** | The height of the new video frame, in points. |
| fname | [System::String](../../../system/string/) | The path or name of the video file to embed. |

### Return Value

The newly created [IVideoFrame](../../ivideoframe/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)