---
title: AddVideo()
second_title: Aspose.Slides for C++ API Reference
description: Adds a copy of an video file from an another presentation.
type: docs
weight: 14
url: /cpp/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo([System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\>) method


Adds a copy of an video file from an another presentation.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
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
* Class [IVideoCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IVideoCollection::AddVideo([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>) method


Creates and adds a video to a presentation from stream.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add video file from. |

### Return Value

Added [IVideo](../../ivideo/).

Deprecated
:   Use AddVideo(Stream stream, LoadingStreamBehavior loadingStreamBehavior). The method will be removed in version 17.10.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideo](../../ivideo/)
* Class [Stream](../../../system.io/stream/)
* Class [IVideoCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IVideoCollection::AddVideo([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>, [LoadingStreamBehavior](../../loadingstreambehavior/)) method


Creates and adds a video to a presentation from stream.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
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
* Class [IVideoCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IVideoCollection::AddVideo([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>) method


Creates and adds a video to a presentation from byte array.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
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
* Class [IVideoCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
