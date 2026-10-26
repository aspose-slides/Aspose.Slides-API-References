---
title: get_RewindAudio()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि प्ले करने के बाद ऑडियो स्वचालित रूप से शुरू में रीवाइंड हो जाता है या नहीं। पढ़ें bool.
type: docs
weight: 235
url: /hi/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() विधि


निर्धारित करता है कि प्ले करने के बाद ऑडियो स्वचालित रूप से शुरू में रीवाइंड हो जाता है या नहीं। पढ़ें **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
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

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## देखें

* क्लास [AudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)