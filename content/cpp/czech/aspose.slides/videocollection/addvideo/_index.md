---
title: AddVideo()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přidá kopii video souboru z jiné prezentace.
type: docs
weight: 53
url: /cs/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) metoda

Přidá kopii video souboru z jiné prezentace.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Zdrojové video. |

### Návratová hodnota

Přidané video.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metoda

Vytvoří a přidá video do prezentace ze streamu.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, ze kterého se přidá video soubor. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Chování, které bude použito na stream. |

### Návratová hodnota

Přidáno [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) metoda

Vytvoří a přidá video do prezentace z pole bajtů.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bajtů. |

### Návratová hodnota

Přidané video.

## Viz také

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IVideo](../../ivideo/)
* Třída [VideoCollection](../)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)