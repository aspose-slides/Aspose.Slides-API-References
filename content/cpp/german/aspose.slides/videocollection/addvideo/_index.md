---
title: AddVideo()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine Kopie einer Videodatei aus einer anderen Präsentation hinzu.
type: docs
weight: 53
url: /de/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) Methode

Fügt eine Kopie einer Videodatei aus einer anderen Präsentation hinzu.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Quellvideo. |

### Rückgabewert

Video hinzugefügt.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) Methode

Erstellt und fügt ein Video aus einem Stream einer Präsentation hinzu.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, aus dem die Videodatei hinzugefügt wird. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Das Verhalten, das auf den Stream angewendet wird. |

### Rückgabewert

[IVideo](../../ivideo/) hinzugefügt.

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) Methode

Erstellt und fügt ein Video aus einem Byte-Array einer Präsentation hinzu.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) Bytes. |

### Rückgabewert

Video hinzugefügt.

## Siehe auch

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IVideo](../../ivideo/)
* Klasse [VideoCollection](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)