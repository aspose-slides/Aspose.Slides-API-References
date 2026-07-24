---
title: AddVideo()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine Kopie einer Videodatei aus einer anderen Präsentation hinzu.
type: docs
weight: 14
url: /de/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) Methode

Fügt eine Kopie einer Videodatei aus einer anderen Präsentation hinzu.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Quellvideo. |

### Rückgabewert

Hinzugefügtes Video.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) Methode

Erstellt und fügt ein Video zu einer Präsentation aus einem Stream hinzu.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, aus dem die Videodatei hinzugefügt wird. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Das Verhalten, das auf den Stream angewendet wird. |

### Rückgabewert

Hinzugefügtes [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) Methode

Erstellt und fügt ein Video zu einer Präsentation aus einem Byte-Array hinzu.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) Bytes. |

### Rückgabewert

Hinzugefügtes Video.

## Siehe auch

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IVideo](../../ivideo/)
* Klasse [IVideoCollection](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)