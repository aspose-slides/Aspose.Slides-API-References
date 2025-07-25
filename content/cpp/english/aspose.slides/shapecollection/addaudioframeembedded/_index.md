---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API Reference
description: "Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. The embedded audio is added to the Presentation::get_Audios collection."
type: docs
weight: 287
url: /aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method


Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. The embedded audio is added to the [Presentation::get_Audios](../../presentation/get_audios/) collection.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | An input stream containing WAV audio data to embed. |

### Return Value

The newly created [IAudioFrame](../../iaudioframe/).
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


Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the [Presentation::get_Audios](../../presentation/get_audios/) list.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | An [IAudio](../../iaudio/) instance from the [Presentation::get_Audios](../../presentation/get_audios/) collection. |

### Return Value

The newly created [IAudioFrame](../../iaudioframe/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)