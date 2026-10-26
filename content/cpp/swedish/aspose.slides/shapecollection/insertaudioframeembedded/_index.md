---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides för C++ API-referens
description: "Skapar en ny ljudram med en inbäddad WAV-fil och infogar den i shape-samlingen på det angivna indexet. Den inbäddade ljudfilen läggs till i Presentation::get_Audios-samlingen."
type: docs
weight: 300
url: /sv/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metod

Skapar en ny ljudram med en inbäddad WAV-fil och infogar den i shape-samlingen på det angivna indexet. Den inbäddade ljudfilen läggs till i [Presentation::get_Audios](../../presentation/get_audios/)-samlingen.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade index där ljudramen ska infogas. |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | En inkommande ström som innehåller WAV-ljuddata att bädda in. |

### Returvärde

Den nyskapade [IAudioFrame](../../iaudioframe/).

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metod

Skapar en ny ljudram och infogar den i shape-samlingen på det angivna indexet med ett befintligt ljudobjekt från [Presentation::get_Audios](../../presentation/get_audios/)-listan.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade index där ljudramen ska infogas. |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | En [IAudio](../../iaudio/)-instans från [Presentation::get_Audios](../../presentation/get_audios/)-samlingen att bädda in. |

### Returvärde

Den nyskapade [IAudioFrame](../../iaudioframe/).

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudioFrame](../../iaudioframe/)
* Klass [Stream](../../../system.io/stream/)
* Klass [ShapeCollection](../)
* Klass [IAudio](../../iaudio/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)