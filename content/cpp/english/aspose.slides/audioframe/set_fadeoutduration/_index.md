---
title: set_FadeOutDuration()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the time duration for the ending fade-out of the media in milliseconds. Write float.
type: docs
weight: 365
url: /aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) method


Specifies the time duration for the ending fade-out of the media in milliseconds. Write **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Add Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the ending fade for 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## See Also

* Class [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)