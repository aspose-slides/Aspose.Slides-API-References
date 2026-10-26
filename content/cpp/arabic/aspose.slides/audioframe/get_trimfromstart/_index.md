---
title: get_TrimFromStart()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. قراءة float.
type: docs
weight: 404
url: /ar/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() طريقة


يحدد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية. قراءة **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تعيين وقت القطع من البداية 1.5 ثانية
audioFrame->set_TrimFromStart(1500.0f);
```

## انظر أيضًا

* فئة [AudioFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)