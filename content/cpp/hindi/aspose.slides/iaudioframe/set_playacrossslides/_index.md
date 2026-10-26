---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्धारित करता है कि ऑडियो स्लाइड्स के पार चल रहा है या नहीं। लिखें **bool**.
type: docs
weight: 222
url: /hi/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) मेथड

निर्धारित करता है कि क्या ऑडियो स्लाइड्स के पार चल रहा है। लिखें **bool**।

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ऑडियो को स्लाइड्स के पार चलाने के लिए सेट करें
audioFrame->set_PlayAcrossSlides(true);

// प्ले होने के बाद ऑडियो को स्वचालित रूप से शुरू में रीवाइंड करने के लिए सेट करें
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## अन्य देखें

* क्लास [IAudioFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)