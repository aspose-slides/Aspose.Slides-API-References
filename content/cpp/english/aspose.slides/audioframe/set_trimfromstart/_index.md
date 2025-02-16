---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. Write float.
type: docs
weight: 417
url: /aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) method


Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. Write **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Add Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the start trimming time 1.5 seconds
audioFrame->set_TrimFromStart(1500.0f);
```

## See Also

* Class [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)