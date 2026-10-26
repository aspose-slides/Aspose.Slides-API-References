---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides voor C++ API-referentie
description: "Maakt een nieuw audioframe met een ingesloten WAV-bestand en voegt het in de vormverzameling in op de opgegeven index. De ingesloten audio wordt toegevoegd aan de Presentation::get_Audios collectie."
type: docs
weight: 300
url: /nl/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) methode


Maakt een nieuw audioframe met een ingesloten WAV-bestand en voegt het in de vormverzameling in op de opgegeven index. De ingesloten audio wordt toegevoegd aan de [Presentation::get_Audios](../../presentation/get_audios/) collectie.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het audioframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe audioframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audioframe, in punten. |
| width | **float** | De breedte van het nieuwe audioframe, in punten. |
| height | **float** | De hoogte van het nieuwe audioframe, in punten. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een invoerstroom die WAV-audiodata bevat om in te sluiten. |

### Retourwaarde

Het nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) methode


Maakt een nieuw audioframe en voegt het in de vormverzameling in op de opgegeven index met behulp van een bestaand audio-object uit de [Presentation::get_Audios](../../presentation/get_audios/) lijst.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het audioframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe audioframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audioframe, in punten. |
| width | **float** | De breedte van het nieuwe audioframe, in punten. |
| height | **float** | De hoogte van het nieuwe audioframe, in punten. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Een [IAudio](../../iaudio/)-instantie uit de [Presentation::get_Audios](../../presentation/get_audios/) collectie om in te sluiten. |

### Retourwaarde

Het nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioFrame](../../iaudioframe/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ShapeCollection](../)
* Klasse [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)