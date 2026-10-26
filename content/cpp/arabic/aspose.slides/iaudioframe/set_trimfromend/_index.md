---
title: set_TrimFromEnd()
second_title: Aspose.Slides لمرجع واجهة برمجة التطبيقات C++
description: يحدد مدة الوقت التي يجب إزالتها من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. اكتب float.
type: docs
weight: 443
url: /ar/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) طريقة

يحدد مدة الوقت التي يجب إزالتها من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. كتابة **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تعيين وقت القص من النهاية 2 ثانية
audioFrame->set_TrimFromEnd(2000.0f);
```

## انظر أيضًا

* فئة [IAudioFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)