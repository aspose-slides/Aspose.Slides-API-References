---
title: set_RewindAudio()
second_title: Aspose.Slides للـ C++ مرجع API
description: يحدد ما إذا كان يتم إعادة تشغيل الصوت تلقائيًا إلى البداية بعد التشغيل. اكتب bool.
type: docs
weight: 248
url: /ar/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) method


يحدد ما إذا كان يتم إعادة تشغيل الصوت تلقائيًا إلى البداية بعد التشغيل. اكتب **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// إضافة إطار صوت
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// تعيين الصوت لتشغيله عبر الشرائح
audioFrame->set_PlayAcrossSlides(true);

// تعيين الصوت لإعادة تشغيله تلقائيًا إلى البداية بعد التشغيل
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [AudioFrame](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)