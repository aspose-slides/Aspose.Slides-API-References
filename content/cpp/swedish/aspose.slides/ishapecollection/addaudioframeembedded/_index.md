---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny ljudram med en inbäddad WAV-fil och lägger till den i slutet av shape-samlingen. Det inbäddade ljudet läggs till i Presentation.Audios-samlingen.
type: docs
weight: 248
url: /sv/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metod


Skapar en ny ljudram med en inbäddad WAV-fil och lägger till den i slutet av shape collection. Det inbäddade ljudet läggs till i Presentation.Audios collection.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | En inmatningsström som innehåller WAV-ljuddata att bädda in. |

### Returvärde

Det nyss skapade [IAudioFrame](../../iaudioframe/).

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) metod


Skapar en ny ljudram och lägger till den i slutet av shape collection med ett befintligt ljudobjekt från Presentation.Audios listan.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | En [IAudio](../../iaudio/)-instans från Presentation.Audios-samlingen. |

### Returvärde

Det nyss skapade [IAudioFrame](../../iaudioframe/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudioFrame](../../iaudioframe/)
* Klass [Stream](../../../system.io/stream/)
* Klass [IShapeCollection](../)
* Klass [IAudio](../../iaudio/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)