---
title: get_RewindAudio()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether an audio is automatically rewinded to start after playing. Read bool.
type: docs
weight: 235
url: /aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() method


Determines whether an audio is automatically rewinded to start after playing. Read **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## Remarks



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## See Also

* Class [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)