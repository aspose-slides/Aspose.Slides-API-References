---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides के लिए C++ एपीआई संदर्भ
description: निर्धारित करता है कि ऑडियो स्लाइड्स के बीच चल रहा है या नहीं। bool लिखें।
type: docs
weight: 222
url: /hi/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) विधि


स्लाइड्स के बीच ऑडियो चल रहा है या नहीं निर्धारित करता है। **bool** लिखें।

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ऑडियो को स्लाइड्स के बीच चलाने के लिए सेट करें
audioFrame->set_PlayAcrossSlides(true);

// चलने के बाद ऑडियो को स्वचालित रूप से शुरू में रीवाइंड करने के लिए सेट करें
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## संबंधित देखें

* क्लास [AudioFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)