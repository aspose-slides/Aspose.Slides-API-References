---
title: set_FadeInDuration()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد مدة الوقت للظهور التدريجي الأولي للوسائط بالمللي ثانية. اكتب float.
type: docs
weight: 339
url: /ar/aspose.slides/audioframe/set_fadeinduration/
---
## AudioFrame::set_FadeInDuration(float) طريقة

يحدد مدة الوقت للظهور التدريجي الأولي للوسائط بالمللي ثانية. اكتب **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeInDuration(float value) override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تحديد مدة الظهور التدريجي الأولي بـ 200 مللي ثانية
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [AudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)