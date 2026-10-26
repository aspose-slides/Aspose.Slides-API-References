---
title: set_TrimFromStart()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد مدة الوقت التي يجب إزالتها من بداية الوسائط أثناء التشغيل، بالميليثانية. اكتب float.
type: docs
weight: 417
url: /ar/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) طريقة

حدد المدة الزمنية التي يجب إزالتها من بداية الوسائط أثناء التشغيل، بالميليثانية. اكتب **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## ملاحظات


مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تعيين وقت القص من البداية 1.5 ثانية
audioFrame->set_TrimFromStart(1500.0f);
```

## انظر أيضًا

* الفئة [AudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)