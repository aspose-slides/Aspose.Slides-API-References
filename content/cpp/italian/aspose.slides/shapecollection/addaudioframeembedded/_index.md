---
title: AddAudioFrameEmbedded()
second_title: Riferimento API di Aspose.Slides per C++
description: "Crea un nuovo fotogramma audio con un file WAV incorporato e lo aggiunge alla fine della collezione di forme. L'audio incorporato viene aggiunto alla collezione Presentation::get_Audios."
type: docs
weight: 287
url: /it/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method

Crea un nuovo fotogramma audio con un file WAV incorporato e lo aggiunge alla fine della collection di forme. L'audio incorporato viene aggiunto alla [Presentation::get_Audios](../../presentation/get_audios/) collection.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo fotogramma audio, in punti. |
| y | **float** | La coordinata y del nuovo fotogramma audio, in punti. |
| width | **float** | La larghezza del nuovo fotogramma audio, in punti. |
| height | **float** | L'altezza del nuovo fotogramma audio, in punti. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flusso di input contenente dati audio WAV da incorporare. |

### Valore di ritorno

Il nuovo [IAudioFrame](../../iaudioframe/) creato.

## Osservazioni

Il seguente esempio mostra come creare il Frame [Audio](../../audio/). 
```cpp
// Istanzia una classe Presentation che rappresenta un file di presentazione
auto pres = System::MakeObject<Presentation>();

// Ottiene la prima diapositiva
auto slide = pres->get_Slides()->idx_get(0);
// Carica il file audio wav nello stream
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Aggiunge il fotogramma audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Imposta la modalità di riproduzione e il volume dell'audio
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Scrive il file PowerPoint su disco
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method

Crea un nuovo fotogramma audio e lo aggiunge alla fine della collection di forme utilizzando un oggetto audio esistente dalla lista [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo fotogramma audio, in punti. |
| y | **float** | La coordinata y del nuovo fotogramma audio, in punti. |
| width | **float** | La larghezza del nuovo fotogramma audio, in punti. |
| height | **float** | L'altezza del nuovo fotogramma audio, in punti. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Una istanza [IAudio](../../iaudio/) dalla collezione [Presentation::get_Audios](../../presentation/get_audios/). |

### Valore di ritorno

Il nuovo [IAudioFrame](../../iaudioframe/) creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)