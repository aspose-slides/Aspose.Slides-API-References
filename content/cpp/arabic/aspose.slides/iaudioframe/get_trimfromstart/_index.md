---
title: get_TrimFromStart()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يحدد مدة الوقت التي يجب إزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. قراءة float.
type: docs
weight: 404
url: /ar/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() طريقة


يحدد مدة الوقت التي يجب إزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. قراءة **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تعيين وقت القص من البداية 1.5 ثانية
audioFrame->set_TrimFromStart(1500.0f);
```

## انظر أيضًا

* الفئة [IAudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)