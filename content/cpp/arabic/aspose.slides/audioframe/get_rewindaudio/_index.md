---
title: get_RewindAudio()
second_title: Aspose.Slides لمرجع API للغة C++
description: يحدد ما إذا كان الصوت يُعاد تشغيله تلقائيًا من البداية بعد التشغيل. قراءة bool.
type: docs
weight: 235
url: /ar/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() طريقة


يحدد ما إذا كان الصوت يُعاد تشغيله تلقائيًا من البداية بعد التشغيل. قراءة **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## ملاحظات


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// إضافة إطار صوتي
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ضبط تشغيل الصوت عبر الشرائح
audioFrame->set_PlayAcrossSlides(true);

// ضبط الصوت لإعادة التشغيل تلقائيًا إلى البداية بعد التشغيل
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [AudioFrame](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)