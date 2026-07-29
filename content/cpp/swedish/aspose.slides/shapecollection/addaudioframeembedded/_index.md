---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides för C++ API-referens
description: "Skapar en ny ljudram med en inbäddad WAV-fil och lägger till den i slutet av shape-samlingen. Det inbäddade ljudet läggs till i samlingen Presentation::get_Audios."
type: docs
weight: 287
url: /sv/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metod


Skapar en ny ljudram med en inbäddad WAV-fil och lägger till den i slutet av shape-samlingen. Den inbäddade ljudfilen läggs till i samlingen [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | En indataström som innehåller WAV-ljuddata att bädda in. |

### Returvärde

Den nyss skapade [IAudioFrame](../../iaudioframe/).

## Anmärkningar



Följande exempel visar hur man skapar [Audio](../../audio/)-ramen. 
```cpp
// Skapar en presentationsklass som representerar en presentationsfil
auto pres = System::MakeObject<Presentation>();

// Hämtar den första bilden
auto slide = pres->get_Slides()->idx_get(0);
// Laddar wav-ljudfilen till en ström
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Lägger till ljudramen
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Ställer in uppspelningsläge och volym för ljudet
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Skriver PowerPoint-filen till disk
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) metod


Skapar en ny ljudram och lägger till den i slutet av shape-samlingen med ett befintligt ljudobjekt från listan [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | En [IAudio](../../iaudio/)-instans från samlingen [Presentation::get_Audios](../../presentation/get_audios/). |

### Returvärde

Den nyss skapade [IAudioFrame](../../iaudioframe/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudioFrame](../../iaudioframe/)
* Klass [Stream](../../../system.io/stream/)
* Klass [ShapeCollection](../)
* Klass [IAudio](../../iaudio/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)