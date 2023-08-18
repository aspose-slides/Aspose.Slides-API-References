---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new video frame to the end of a collection.
type: docs
weight: 170
url: /aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) method


Adds a new video frame to the end of a collection.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new video frame. |
| y | **float** | Y coordinate of a new video frame. |
| width | **float** | Width of a new video frame. |
| height | **float** | Height of a new video frame. |
| fname | [System::String](../../../system/string/) | [Video](../../video/) file name. |

### Return Value

Created [VideoFrame](../../videoframe/) object.

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) method


Adds a new video frame to the end of a collection.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new video frame. |
| y | **float** | Y coordinate of a new video frame. |
| width | **float** | Width of a new video frame. |
| height | **float** | Height of a new video frame. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [Video](../../video/). |

### Return Value

Created [VideoFrame](../../videoframe/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [IShapeCollection](../)
* Class [IVideo](../../ivideo/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)