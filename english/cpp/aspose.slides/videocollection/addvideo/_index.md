---
title: AddVideo()
second_title: Aspose.Slides for C++ API Reference
description: Adds a copy of an video file from an another presentation.
type: docs
weight: 53
url: /cpp/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo([System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\>) method


Adds a copy of an video file from an another presentation.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Source video. |

### Return Value

Added video.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideo](../../ivideo/)
* Class [VideoCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## VideoCollection::AddVideo([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>) method


Creates and adds a video to a presentation from stream.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add video file from. |

### Return Value

Added [Video](../../video/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideo](../../ivideo/)
* Class [Stream](../../../system.io/stream/)
* Class [VideoCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## VideoCollection::AddVideo([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>, [LoadingStreamBehavior](../../loadingstreambehavior/)) method


Creates and adds a video to a presentation from stream.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add video file from. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | The behavior which will be applied to the stream. |

### Return Value

Added [IVideo](../../ivideo/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideo](../../ivideo/)
* Class [Stream](../../../system.io/stream/)
* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Class [VideoCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## VideoCollection::AddVideo([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>) method


Creates and adds a video to a presentation from byte array.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bytes. |

### Return Value

Added video.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideo](../../ivideo/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [VideoCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
