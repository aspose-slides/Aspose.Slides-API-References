---
title: get_TrimFromEnd()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the time duration to be removed from the end of the media during playback, in milliseconds. Read float.
type: docs
weight: 430
url: /aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() method


Specifies the time duration to be removed from the end of the media during playback, in milliseconds. Read **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Add Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the end trimming time 2 seconds
audioFrame->set_TrimFromEnd(2000.0f);
```

## See Also

* Class [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)