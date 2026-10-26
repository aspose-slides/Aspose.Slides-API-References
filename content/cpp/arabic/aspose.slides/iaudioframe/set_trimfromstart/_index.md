---
title: set_TrimFromStart()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد مدة الوقت التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالميليثانية. اكتب float.
type: docs
weight: 417
url: /ar/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) طريقة


يحدد مدة الزمن التي سيتم إزالتها من بداية الوسائط أثناء التشغيل، بالميلي ثانية. اكتب **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تحديد وقت القص من البداية 1.5 ثانية
audioFrame->set_TrimFromStart(1500.0f);
```

## انظر أيضًا

* الفئة [IAudioFrame](../)
* مساحة الأسماء [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)