---
title: set_VolumeValue()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط مستوى الصوت بالنسب المئوية. اكتب float.
type: docs
weight: 391
url: /ar/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) طريقة

يضبط مستوى الصوت في النسب المئوية. اكتب **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوت
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ضبط مدة التلاشي الابتدائي إلى 200 مللي ثانية
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* الفئة [AudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)