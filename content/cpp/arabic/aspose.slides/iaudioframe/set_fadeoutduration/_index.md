---
title: set_FadeOutDuration()
second_title: Aspose.Slides لمرجع API C++
description: يحدد مدة الوقت للانخفاض التدريجي النهائي للوسائط بالمللي ثانية. اكتب float.
type: docs
weight: 365
url: /ar/aspose.slides/iaudioframe/set_fadeoutduration/
---
## IAudioFrame::set_FadeOutDuration(float) طريقة

يحدد مدة الوقت للانخفاض التدريجي النهائي للوسائط بالمللي ثانية. اكتب **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeOutDuration(float value)=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوت
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تحديد مدة الانخفاض التدريجي النهائي إلى 500 مللي ثانية
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [IAudioFrame](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)