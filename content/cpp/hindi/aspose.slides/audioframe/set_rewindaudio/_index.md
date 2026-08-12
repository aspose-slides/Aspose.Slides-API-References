---
title: set_RewindAudio()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि क्या ऑडियो को चलने के बाद स्वतः प्रारम्भ पर रीवाइंड किया जाता है। लिखें bool.
type: docs
weight: 248
url: /hi/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) विधि


निर्धारित करता है कि क्या ऑडियो को चलने के बाद स्वतः प्रारंभ पर रीवाइंड किया जाता है। लिखें **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ऑडियो को सभी स्लाइडों में चलाने के लिए सेट करें
audioFrame->set_PlayAcrossSlides(true);

// चलने के बाद ऑडियो को स्वतः प्रारम्भ पर रीवाइंड करने के लिए सेट करें
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## संबंधित देखें

* क्लास [AudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)