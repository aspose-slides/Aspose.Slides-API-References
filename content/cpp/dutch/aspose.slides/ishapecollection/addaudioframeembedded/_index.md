---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het toe aan het einde van de shape-collectie. De ingesloten audio wordt toegevoegd aan de Presentation.Audios-collectie.
type: docs
weight: 248
url: /nl/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method

Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het toe aan het einde van de shape-collectie. De ingesloten audio wordt toegevoegd aan de Presentation.Audios-collectie.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | **float** | De breedte van het nieuwe audio-frame, in punten. |
| height | **float** | De hoogte van het nieuwe audio-frame, in punten. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een invoerstroom met WAV-audiogegevens om in te sluiten. |

### Retourwaarde

Het nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method

Maakt een nieuw audio-frame en voegt het toe aan het einde van de shape-collectie met behulp van een bestaand audio-object uit de Presentation.Audios-lijst.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | **float** | De breedte van het nieuwe audio-frame, in punten. |
| height | **float** | De hoogte van het nieuwe audio-frame, in punten. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Een [IAudio](../../iaudio/)-instance uit de Presentation.Audios-collectie. |

### Retourwaarde

Het nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioFrame](../../iaudioframe/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [IShapeCollection](../)
* Klasse [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)