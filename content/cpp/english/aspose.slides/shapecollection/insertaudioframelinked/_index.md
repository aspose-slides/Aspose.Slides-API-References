---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index.
type: docs
weight: 274
url: /aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) method


Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| fname | [System::String](../../../system/string/) | The path or name of the external audio file to link. |

### Return Value

The newly created [IAudioFrame](../../iaudioframe/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)