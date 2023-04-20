---
title: set_RewindAudio()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether an audio is automatically rewinded to start after playing. Write bool.
type: docs
weight: 248
url: /cpp/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) method


Determines whether an audio is automatically rewinded to start after playing. Write **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
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

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```




## See Also

* Class [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)