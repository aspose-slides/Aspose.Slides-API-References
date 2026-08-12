---
title: get_RewindAudio()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าการเล่นเสียงจะถูกรีวินด์กลับไปยังจุดเริ่มต้นโดยอัตโนมัติหรือไม่ อ่าน bool.
type: docs
weight: 235
url: /th/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() เมธอด


กำหนดว่าการเล่นเสียงจะถูกรีวินด์ไปยังจุดเริ่มต้นโดยอัตโนมัติหรือไม่ อ่าน **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// เพิ่ม Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)