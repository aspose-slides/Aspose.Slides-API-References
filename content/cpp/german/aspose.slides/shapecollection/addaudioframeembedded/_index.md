---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides für C++ API-Referenz
description: "Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn am Ende der ShapeCollection hinzu. Die eingebettete Audiodatei wird zur Presentation::get_Audios Sammlung hinzugefügt."
type: docs
weight: 287
url: /de/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) Methode

Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn am Ende der ShapeCollection hinzu. Die eingebettete Audiodatei wird zur [Presentation::get_Audios](../../presentation/get_audios/)-Sammlung hinzugefügt.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Die X-Koordinate des neuen Audio-Frames, in Punkten. |
| y | **float** | Die Y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames, in Punkten. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |

### Rückgabewert

Der neu erstellte [IAudioFrame](../../iaudioframe/).

## Anmerkungen

Das folgende Beispiel zeigt, wie man einen [Audio](../../audio/)-Frame erstellt. 
```cpp
// Instanziiert eine Präsentationsklasse, die eine Präsentationsdatei darstellt
auto pres = System::MakeObject<Presentation>();

// Liest die erste Folie
auto slide = pres->get_Slides()->idx_get(0);
// Lädt die WAV-Sounddatei in einen Stream
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Fügt den Audio-Frame hinzu
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Setzt den Wiedergabemodus und die Lautstärke des Audios
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Schreibt die PowerPoint-Datei auf die Festplatte
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) Methode

Erstellt einen neuen Audio-Frame und fügt ihn am Ende der ShapeCollection hinzu, indem ein vorhandenes Audio-Objekt aus der [Presentation::get_Audios](../../presentation/get_audios/)-Liste verwendet wird.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Die X-Koordinate des neuen Audio-Frames, in Punkten. |
| y | **float** | Die Y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames, in Punkten. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Eine [IAudio](../../iaudio/)-Instanz aus der [Presentation::get_Audios](../../presentation/get_audios/)-Sammlung. |

### Rückgabewert

Der neu erstellte [IAudioFrame](../../iaudioframe/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioFrame](../../iaudioframe/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ShapeCollection](../)
* Klasse [IAudio](../../iaudio/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)