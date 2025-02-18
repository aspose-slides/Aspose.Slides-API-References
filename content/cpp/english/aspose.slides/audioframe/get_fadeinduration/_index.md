---
title: get_FadeInDuration()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the time duration for the initial fade-in of the media in milliseconds. Read float.
type: docs
weight: 326
url: /aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() method


Specifies the time duration for the initial fade-in of the media in milliseconds. Read **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Add Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## See Also

* Class [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)