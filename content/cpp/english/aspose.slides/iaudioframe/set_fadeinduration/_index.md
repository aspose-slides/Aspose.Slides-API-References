---
title: set_FadeInDuration()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the time duration for the initial fade-in of the media in milliseconds. Write float.
type: docs
weight: 339
url: /aspose.slides/iaudioframe/set_fadeinduration/
---
## IAudioFrame::set_FadeInDuration(float) method


Specifies the time duration for the initial fade-in of the media in milliseconds. Write **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeInDuration(float value)=0
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

* Class [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)