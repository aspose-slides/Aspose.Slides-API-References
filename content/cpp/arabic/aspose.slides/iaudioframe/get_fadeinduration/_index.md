---
title: get_FadeInDuration()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد مدة الوقت للظهور التدريجي الأولي للوسائط بالمللي ثانية. قراءة float.
type: docs
weight: 326
url: /ar/aspose.slides/iaudioframe/get_fadeinduration/
---
## IAudioFrame::get_FadeInDuration() طريقة

يحدد مدة الوقت للظهور التدريجي الأولي للوسائط بالمللي ثانية. قراءة **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeInDuration()=0
```

## ملاحظات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوت
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [IAudioFrame](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)