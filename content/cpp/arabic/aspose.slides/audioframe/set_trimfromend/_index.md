---
title: set_TrimFromEnd()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: يحدد مدة الزمن التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. اكتب float.
type: docs
weight: 443
url: /ar/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) طريقة

يحدد مدة الزمن التي سيتم إزالتها من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. اكتب **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوت
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the end trimming time 2 seconds
audioFrame->set_TrimFromEnd(2000.0f);
```

## انظر أيضًا

* الفئة [AudioFrame](../)
* المجال [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)