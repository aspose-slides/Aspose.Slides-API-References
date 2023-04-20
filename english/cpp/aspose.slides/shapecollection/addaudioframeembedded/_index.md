---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API Reference
description: "Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation::get_Audios list."
type: docs
weight: 287
url: /cpp/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method


Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into [Presentation::get_Audios](../../presentation/get_audios/) list.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new audio frame. |
| y | **float** | Y coordinate of a new audio frame. |
| width | **float** | Width of a new audio frame. |
| height | **float** | Height of a new audio frame. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Inout stream with audio data. |

### Return Value

Created [AudioFrame](../../audioframe/) object.
## Remarks



The following examples shows how to create [Audio](../../audio/) Frame. 
```cpp
// Instantiates a presentation class that represents a presentation file
auto pres = System::MakeObject<Presentation>();

// Gets the first slide
auto slide = pres->get_Slides()->idx_get(0);
// Loads the the wav sound file to stream
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Adds the Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Sets the Play Mode and Volume of the Audio
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Writes the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method


Adds a new audio frame with embedded audio file to the end of a collection. It uses audio file from [Presentation::get_Audios](../../presentation/get_audios/) list.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new audio frame. |
| y | **float** | Y coordinate of a new audio frame. |
| width | **float** | Width of a new audio frame. |
| height | **float** | Height of a new audio frame. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | [Audio](../../audio/) from [Presentation::get_Audios](../../presentation/get_audios/) list. |

### Return Value

Created [AudioFrame](../../audioframe/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)