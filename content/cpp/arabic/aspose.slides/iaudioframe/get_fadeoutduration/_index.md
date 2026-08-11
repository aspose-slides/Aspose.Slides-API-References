---
title: get_FadeOutDuration()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد مدة الوقت للانخفاض النهائي للوسائط بالملي ثانية. قراءة float.
type: docs
weight: 352
url: /ar/aspose.slides/iaudioframe/get_fadeoutduration/
---
## IAudioFrame::get_FadeOutDuration() طريقة

يحدد مدة الوقت للانخفاض النهائي للوسائط بالملي ثانية. قراءة **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeOutDuration()=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تعيين مدة الانخفاض النهائي إلى 500 مللي ثانية
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## انظر أيضا

* الفئة [IAudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)