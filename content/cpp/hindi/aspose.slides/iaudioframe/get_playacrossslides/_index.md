---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides C++ के लिए एपीआई संदर्भ
description: निश्चित करता है कि क्या ऑडियो स्लाइड्स के बीच बज रहा है। पढ़ें bool.
type: docs
weight: 209
url: /hi/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() विधि


निर्धारित करता है कि क्या ऑडियो स्लाइड्स के बीच बज रहा है। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ऑडियो को स्लाइड्स के बीच बजाने के लिए सेट करें
audioFrame->set_PlayAcrossSlides(true);

// ऑडियो को प्ले होने के बाद स्वचालित रूप से शुरुआत पर रिवाइंड करने के लिए सेट करें
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## देखें

* क्लास [IAudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)