---
title: get_RewindAudio()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्धारित करता है कि क्या ऑडियो प्ले होने के बाद स्वचालित रूप से शुरू में पुनः-संचालित किया जाता है। पढ़ें bool.
type: docs
weight: 235
url: /hi/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() विधि

निर्धारित करता है कि क्या ऑडियो प्ले होने के बाद स्वचालित रूप से शुरू में पुनः-संचालित किया जाता है। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## टिप्पणी

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ऑडियो को स्लाइडों के बीच चलाने के लिए सेट करें
audioFrame->set_PlayAcrossSlides(true);

// प्ले होने के बाद ऑडियो को स्वचालित रूप से शुरू में रीवाइंड करने के लिए सेट करें
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* वर्ग [IAudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)