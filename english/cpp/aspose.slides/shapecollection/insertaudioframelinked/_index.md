---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new audio frame with linked audio file and inserts it to a collection at the specified index.
type: docs
weight: 274
url: /cpp/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) method


Creates a new audio frame with linked audio file and inserts it to a collection at the specified index.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which audio frame should be inserted. |
| x | **float** | X coordinate of a new audio frame. |
| y | **float** | Y coordinate of a new audio frame. |
| width | **float** | Width of a new audio frame. |
| height | **float** | Height of a new audio frame. |
| fname | [System::String](../../../system/string/) | [Audio](../../audio/) file name. |

### Return Value

Created [AudioFrame](../../audioframe/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)