---
title: set_RewindAudio()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि क्या ऑडियो प्ले करने के बाद स्वचालित रूप से शुरू से पुनः चलाया जाता है। लिखें bool.
type: docs
weight: 248
url: /hi/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) विधि

निर्धारित करता है कि क्या ऑडियो प्ले करने के बाद स्वचालित रूप से शुरू से पुनः चलाया जाता है। लिखें **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## टिप्पणी



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




## देखें

* क्लास [IAudioFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)