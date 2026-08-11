---
title: set_VolumeValue()
second_title: مرجع API Aspose.Slides لـ C++
description: يضبط مستوى الصوت بالنسبة المئوية. اكتب float.
type: docs
weight: 391
url: /ar/aspose.slides/iaudioframe/set_volumevalue/
---
## IAudioFrame::set_VolumeValue(float) طريقة


يضبط مستوى الصوت بالنسبة المئوية. اكتب **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_VolumeValue(float value)=0
```

## ملاحظات


مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// أضف إطار صوت
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// اضبط مدة التلاشي الأولي إلى 200 مللي ثانية
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [IAudioFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)