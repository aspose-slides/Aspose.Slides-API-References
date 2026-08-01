---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw audioframe met een ingebed WAV-bestand en voegt het toe aan de vormverzameling op de opgegeven index. Het ingebedde audio wordt toegevoegd aan de Presentation.Audios-collectie.
type: docs
weight: 261
url: /nl/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) methode


Maakt een nieuw audioframe met een ingebed WAV-bestand en voegt het toe aan de vormverzameling op de opgegeven index. Het ingebedde audio wordt toegevoegd aan de Presentation.Audios-collectie.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | An input stream containing WAV audio data to embed. |

### Retourwaarde

Het nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) methode


Maakt een nieuw audioframe en voegt het toe aan de vormverzameling op de opgegeven index met behulp van een bestaand audio-object uit de Presentation.Audios-lijst.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | An [IAudio](../../iaudio/) instance from the Presentation.Audios collection to embed. |

### Retourwaarde

Het nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioFrame](../../iaudioframe/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [IShapeCollection](../)
* Klasse [IAudio](../../iaudio/)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)