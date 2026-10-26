---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides pro C++ API Reference
description: "Vytvoří nový audio rámec s vloženým souborem WAV a přidá jej na konec kolekce tvarů. Vložený audio soubor je přidán do kolekce Presentation::get_Audios."
type: docs
weight: 287
url: /cs/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metoda

Vytvoří nový audio rámec s vloženým souborem WAV a přidá jej na konec kolekce tvarů. Vložený audio soubor je přidán do [Presentation::get_Audios](../../presentation/get_audios/) kolekce.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového audio rámce v bodech. |
| y | **float** | Y-souřadnice nového audio rámce v bodech. |
| width | **float** | Šířka nového audio rámce v bodech. |
| height | **float** | Výška nového audio rámce v bodech. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní stream obsahující data WAV audio k vložení. |

### Návratová hodnota

Nově vytvořený [IAudioFrame](../../iaudioframe/).

## Poznámky

Následující příklady ukazují, jak vytvořit [Audio](../../audio/) rámec. 
```cpp
// Vytvoří instanci třídy prezentace, která představuje soubor prezentace
auto pres = System::MakeObject<Presentation>();

// Získá první snímek
auto slide = pres->get_Slides()->idx_get(0);
// Načte soubor wav zvuku do proudu
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Přidá audio rámec
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Nastaví režim přehrávání a hlasitost audia
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Zapíše soubor PowerPoint na disk
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) metoda

Vytvoří nový audio rámec a přidá jej na konec kolekce tvarů pomocí existujícího audio objektu ze seznamu [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového audio rámce v bodech. |
| y | **float** | Y-souřadnice nového audio rámce v bodech. |
| width | **float** | Šířka nového audio rámce v bodech. |
| height | **float** | Výška nového audio rámce v bodech. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Instanci [IAudio](../../iaudio/) ze sbírky [Presentation::get_Audios](../../presentation/get_audios/). |

### Návratová hodnota

Nově vytvořený [IAudioFrame](../../iaudioframe/).

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IAudioFrame](../../iaudioframe/)
* Třída [Stream](../../../system.io/stream/)
* Třída [ShapeCollection](../)
* Třída [IAudio](../../iaudio/)
* Obor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)