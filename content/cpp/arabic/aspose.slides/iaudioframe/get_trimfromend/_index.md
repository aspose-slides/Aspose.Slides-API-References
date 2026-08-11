---
title: get_TrimFromEnd()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد مدة الوقت التي يجب إزالتها من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. قراءة float.
type: docs
weight: 430
url: /ar/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() طريقة


يحدد مدة الوقت التي يجب إزالتها من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. قراءة **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تعيين وقت القطع من النهاية 2 ثانية
audioFrame->set_TrimFromEnd(2000.0f);
```

## انظر أيضًا

* فئة [IAudioFrame](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)