---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides voor C++ API-referentie
description: "Maakt een nieuw audioframe met een ingesloten WAV-bestand en voegt het toe aan het einde van de shape-collectie. Het ingesloten audio wordt toegevoegd aan de Presentation::get_Audios-collectie."
type: docs
weight: 287
url: /nl/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) methode

Creëert een nieuw audioframe met een ingesloten WAV-bestand en voegt het toe aan het einde van de shape-collectie. Het ingesloten audio wordt toegevoegd aan de [Presentation::get_Audios](../../presentation/get_audios/)-collectie.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe audioframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audioframe, in punten. |
| width | **float** | De breedte van het nieuwe audioframe, in punten. |
| height | **float** | De hoogte van het nieuwe audioframe, in punten. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een invoerstroom die WAV-audiogegevens bevat om in te sluiten. |

### Retourwaarde

Het nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## Opmerkingen

De volgende voorbeelden laten zien hoe u een [Audio](../../audio/)-frame maakt. 
```cpp
// Instantieert een presentatieklasse die een presentatiebestand vertegenwoordigt
auto pres = System::MakeObject<Presentation>();

// Haalt de eerste dia op
auto slide = pres->get_Slides()->idx_get(0);
// Laadt het wav-geluidbestand naar een stream
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Voegt het audioframe toe
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Stelt de afspeelmodus en het volume van de audio in
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Schrijft het PowerPoint-bestand naar schijf
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) methode

Creëert een nieuw audioframe en voegt het toe aan het einde van de shape-collectie met behulp van een bestaand audio-object uit de [Presentation::get_Audios](../../presentation/get_audios/)-lijst.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe audioframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audioframe, in punten. |
| width | **float** | De breedte van het nieuwe audioframe, in punten. |
| height | **float** | De hoogte van het nieuwe audioframe, in punten. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Een [IAudio](../../iaudio/)-instance uit de [Presentation::get_Audios](../../presentation/get_audios/)-collectie. |

### Retourwaarde

Het nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)