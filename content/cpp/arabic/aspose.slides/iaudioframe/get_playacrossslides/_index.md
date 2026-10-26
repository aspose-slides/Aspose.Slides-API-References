---
title: get_PlayAcrossSlides()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يحدد ما إذا كان الصوت يُشغل عبر الشرائح. قراءة bool.
type: docs
weight: 209
url: /ar/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() طريقة


يحدد ما إذا كان الصوت يُشغل عبر الشرائح. قراءة **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// إضافة إطار صوت
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ضبط تشغيل الصوت عبر الشرائح
audioFrame->set_PlayAcrossSlides(true);

// تعيين الصوت لإعادة التشغيل تلقائيًا إلى البداية بعد التشغيل
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## انظر أيضًا

* الفئة [IAudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)