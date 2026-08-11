---
title: set_PlayAcrossSlides()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كان الصوت يُشغَّل عبر الشرائح. اكتب bool.
type: docs
weight: 222
url: /ar/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) طريقة

يحدد ما إذا كان الصوت يُشغَّل عبر الشرائح. اكتب **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// إضافة إطار صوتي
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ضبط الصوت للتشغيل عبر الشرائح
audioFrame->set_PlayAcrossSlides(true);

// ضبط الصوت لإعادة التدوير تلقائيًا إلى البداية بعد التشغيل
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [IAudioFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)