---
title: AddAudioFrameEmbedded()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo frame audio con un file WAV incorporato e lo aggiunge alla fine della raccolta di forme. L'audio incorporato viene aggiunto alla raccolta Presentation.Audios.
type: docs
weight: 248
url: /it/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metodo

Crea un nuovo frame audio con un file WAV incorporato e lo aggiunge alla fine della raccolta di forme. L'audio incorporato viene aggiunto alla raccolta Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame audio, in punti. |
| y | **float** | La coordinata y del nuovo frame audio, in punti. |
| width | **float** | La larghezza del nuovo frame audio, in punti. |
| height | **float** | L'altezza del nuovo frame audio, in punti. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flusso di input contenente dati audio WAV da incorporare. |

### Valore restituito

Il [IAudioFrame](../../iaudioframe/) appena creato.

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) metodo

Crea un nuovo frame audio e lo aggiunge alla fine della raccolta di forme utilizzando un oggetto audio esistente dalla lista Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame audio, in punti. |
| y | **float** | La coordinata y del nuovo frame audio, in punti. |
| width | **float** | La larghezza del nuovo frame audio, in punti. |
| height | **float** | L'altezza del nuovo frame audio, in punti. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Un'istanza [IAudio](../../iaudio/) dalla raccolta Presentation.Audios. |

### Valore restituito

Il [IAudioFrame](../../iaudioframe/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [IShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)