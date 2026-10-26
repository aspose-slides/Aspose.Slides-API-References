---
title: get_TrimFromEnd()
second_title: Aspose.Slides للـ C++ مرجع API
description: يحدد مدة الوقت التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالملي ثانية. قراءة float.
type: docs
weight: 430
url: /ar/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() طريقة


يحدد مدة الوقت التي ستُزال من نهاية الوسائط أثناء التشغيل، بالملي ثانية. اقرأ **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## ملاحظات


مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوت
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ضبط وقت القص من النهاية 2 ثانية
audioFrame->set_TrimFromEnd(2000.0f);
```

## انظر أيضًا

* صف [AudioFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)