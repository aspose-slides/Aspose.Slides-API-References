---
title: AddVideo()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en kopia av en videofil från en annan presentation.
type: docs
weight: 14
url: /sv/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) metod


Lägger till en kopia av en videofil från en annan presentation.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Källvideo. |

### Returvärde

Tillagd video.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metod


Skapar och lägger till en video i en presentation från en ström.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ström att lägga till videofil från. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Beteendet som kommer att tillämpas på strömmen. |

### Returvärde

Tillagd [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) metod


Skapar och lägger till en video i en presentation från en bytearray.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) byte. |

### Returvärde

Tillagd video.

## Se också

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IVideo](../../ivideo/)
* Klass [IVideoCollection](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)