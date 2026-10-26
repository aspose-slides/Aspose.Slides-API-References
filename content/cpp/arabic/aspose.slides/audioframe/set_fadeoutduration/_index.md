---
title: set_FadeOutDuration()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد مدة الوقت للانخفاض التدريجي النهائي للوسائط بالمللي ثانية. اكتب float.
type: docs
weight: 365
url: /ar/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) الطريقة


يحدد مدة الوقت للانخفاض التدريجي النهائي للوسائط بالمللي ثانية. اكتب **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## ملاحظات


مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تعيين مدة الانخفاض التدريجي النهائي إلى 500 مللي ثانية
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [AudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)