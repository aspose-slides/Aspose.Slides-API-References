---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny ljudram med en inbäddad WAV-fil och infogar den i shape-samlingen på det angivna indexet. Det inbäddade ljudet läggs till i Presentation.Audios-samlingen.
type: docs
weight: 261
url: /sv/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metod


Skapar en ny ljudram med en inbäddad WAV-fil och infogar den i shape-samlingen på det angivna indexet. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där ljudramen ska infogas. |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | En inmatningsström som innehåller WAV-ljuddata att bädda in. |

### Returvärde

Den nyss skapade [IAudioFrame](../../iaudioframe/).

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metod


Skapar en ny ljudram och infogar den i shape-samlingen på det angivna indexet med ett befintligt ljudobjekt från Presentation.Audios-listan.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där ljudramen ska infogas. |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | En [IAudio](../../iaudio/)-instans från Presentation.Audios-samlingen att bädda in. |

### Returvärde

Den nyss skapade [IAudioFrame](../../iaudioframe/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [IShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)