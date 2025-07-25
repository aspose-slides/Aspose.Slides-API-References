---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new video frame and adds it to the end of the shape collection.
type: docs
weight: 170
url: /aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) method


Creates a new video frame and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new video frame, in points. |
| y | **float** | The y-coordinate of the new video frame, in points. |
| width | **float** | The width of the new video frame, in points. |
| height | **float** | The height of the new video frame, in points. |
| fname | [System::String](../../../system/string/) | The path or name of the video file to embed. |

### Return Value

The newly created [IVideoFrame](../../ivideoframe/).

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) method


Creates a new video frame and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new video frame, in points. |
| y | **float** | The y-coordinate of the new video frame, in points. |
| width | **float** | The width of the new video frame, in points. |
| height | **float** | The height of the new video frame, in points. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | The [IVideo](../../ivideo/) to embed in the video frame. |

### Return Value

The newly created [IVideoFrame](../../ivideoframe/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [IShapeCollection](../)
* Class [IVideo](../../ivideo/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)