---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new video frame to the end of a collection.
type: docs
weight: 209
url: /aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) method


Adds a new video frame to the end of a collection.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
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

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) method


Adds a new video frame to the end of a collection.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new video frame. |
| y | **float** | Y coordinate of a new video frame. |
| width | **float** | Width of a new video frame. |
| height | **float** | Height of a new video frame. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [Video](../../video/) to add. |

### Return Value

Created [VideoFrame](../../videoframe/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Class [IVideo](../../ivideo/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)