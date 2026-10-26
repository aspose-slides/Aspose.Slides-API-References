---
title: InsertAudioFrameEmbedded()
second_title: Riferimento API di Aspose.Slides per C++
description: "Crea un nuovo fotogramma audio con un file WAV incorporato e lo inserisce nella collezione di forme all'indice specificato. L'audio incorporato viene aggiunto alla collezione Presentation::get_Audios."
type: docs
weight: 300
url: /it/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metodo

Crea un nuovo fotogramma audio con un file WAV incorporato e lo inserisce nella collezione di forme all'indice specificato. L'audio incorporato viene aggiunto alla collezione [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il fotogramma audio. |
| x | **float** | La coordinata x del nuovo fotogramma audio, in punti. |
| y | **float** | La coordinata y del nuovo fotogramma audio, in punti. |
| width | **float** | La larghezza del nuovo fotogramma audio, in punti. |
| height | **float** | L'altezza del nuovo fotogramma audio, in punti. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flusso di input contenente dati audio WAV da incorporare. |

### Valore di ritorno

Il nuovo [IAudioFrame](../../iaudioframe/) creato.

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metodo

Crea un nuovo fotogramma audio e lo inserisce nella collezione di forme all'indice specificato utilizzando un oggetto audio esistente dall'elenco [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il fotogramma audio. |
| x | **float** | La coordinata x del nuovo fotogramma audio, in punti. |
| y | **float** | La coordinata y del nuovo fotogramma audio, in punti. |
| width | **float** | La larghezza del nuovo fotogramma audio, in punti. |
| height | **float** | L'altezza del nuovo fotogramma audio, in punti. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Un'istanza [IAudio](../../iaudio/) dalla collezione [Presentation::get_Audios](../../presentation/get_audios/) da incorporare. |

### Valore di ritorno

Il nuovo [IAudioFrame](../../iaudioframe/) creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioFrame](../../iaudioframe/)
* Classe [Stream](../../../system.io/stream/)
* Classe [ShapeCollection](../)
* Classe [IAudio](../../iaudio/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)