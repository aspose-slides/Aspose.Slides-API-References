---
title: AddVideo()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá kopii video souboru z jiné prezentace.
type: docs
weight: 14
url: /cs/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) metoda


Přidá kopii video souboru z jiné prezentace.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Zdrojové video. |

### Návratová hodnota

Přidáno video.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metoda


Vytvoří a přidá video do prezentace ze streamu.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, ze kterého se přidá soubor videa. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Chování, které bude použito na stream. |

### Návratová hodnota

Přidáno [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) metoda


Vytvoří a přidá video do prezentace z pole bajtů.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bajtů. |

### Návratová hodnota

Přidáno video.

## Viz také

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IVideo](../../ivideo/)
* Třída [IVideoCollection](../)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)