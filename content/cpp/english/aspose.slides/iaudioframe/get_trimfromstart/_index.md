---
title: get_TrimFromStart()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. Read float.
type: docs
weight: 404
url: /aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() method


Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. Read **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
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

* Class [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)