---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides C++ API Referencia
description: "Új hangkeretet hoz létre beágyazott WAV fájllal, és a alakzatgyűjtemény végéhez adja. A beágyazott hang a Presentation::get_Audios gyűjteményhez kerül."
type: docs
weight: 287
url: /hu/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metódus

Új audio keretet hoz létre beágyazott WAV fájllal, és hozzáadja a alakzatgyűjtemény végéhez. A beágyazott hang a [Presentation::get_Audios](../../presentation/get_audios/) gyűjteményhez kerül.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új audio keret x-koordinátája pontban. |
| y | **float** | Az új audio keret y-koordinátája pontban. |
| width | **float** | Az új audio keret szélessége pontban. |
| height | **float** | Az új audio keret magassága pontban. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Egy bemeneti adatfolyam, amely beágyazandó WAV hangadatot tartalmaz. |

### Visszatérési érték

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## Megjegyzések

A következő példák bemutatják, hogyan lehet létrehozni a [Audio](../../audio/) keretet. 
```cpp
// Példányosít egy prezentáció osztályt, amely egy prezentációfájlt képvisel
auto pres = System::MakeObject<Presentation>();

// Lekéri az első diát
auto slide = pres->get_Slides()->idx_get(0);
// Betölti a wav hangfájlt adatfolyamra
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Hozzáadja az Audio keretet
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Beállítja a lejátszási módot és a hangerőt az audiohoz
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// A PowerPoint fájlt leírja a lemezen
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) metódus

Új audio keretet hoz létre, és a alakzatgyűjtemény végéhez adja, a [Presentation::get_Audios](../../presentation/get_audios/) listából származó meglévő audio objektum használatával.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új audio keret x-koordinátája pontban. |
| y | **float** | Az új audio keret y-koordinátája pontban. |
| width | **float** | Az új audio keret szélessége pontban. |
| height | **float** | Az új audio keret magassága pontban. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Egy [IAudio](../../iaudio/) példány a [Presentation::get_Audios](../../presentation/get_audios/) gyűjteményből. |

### Visszatérési érték

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudioFrame](../../iaudioframe/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [ShapeCollection](../)
* Osztály [IAudio](../../iaudio/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)