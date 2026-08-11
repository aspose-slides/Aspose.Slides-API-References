---
title: get_FadeOutDuration()
second_title: Aspose.Slides للغة C++ مرجع API
description: يحدد مدة الوقت للانتهاء من التلاشي التدريجي للوسائط بالمليثانية. قراءة float.
type: docs
weight: 352
url: /ar/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() طريقة

يحدد مدة الوقت للانتهاء من التلاشي التدريجي للوسائط بالمليثانية. قراءة **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ضبط مدة التلاشي النهائي إلى 500 مللي ثانية
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [AudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)