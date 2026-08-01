---
title: AddVideo()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een videobestand toe vanuit een andere presentatie.
type: docs
weight: 14
url: /nl/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) methode

Voegt een kopie van een video-bestand toe vanuit een andere presentatie.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Bron video. |

### Retourwaarde

Toegevoegde video.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) methode

Maakt een video aan en voegt deze toe aan een presentatie vanuit een stream.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream om videobestand van toe te voegen. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Het gedrag dat op de stream zal worden toegepast. |

### Retourwaarde

Toegevoegd [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) methode

Maakt een video aan en voegt deze toe aan een presentatie vanuit een byte-array.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bytes. |

### Retourwaarde

Toegevoegde video.

## Zie ook

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IVideo](../../ivideo/)
* Klasse [IVideoCollection](../)
* Klasse [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)