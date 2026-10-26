---
title: set_RewindAudio()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: กำหนดว่าการเล่นเสียงจะถูกรีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากการเล่นหรือไม่ เขียน bool.
type: docs
weight: 248
url: /th/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) เมธอด


กำหนดว่าการเล่นเสียงจะถูกรีวินด์อัตโนมัติไปยังจุดเริ่มต้นหรือไม่ เขียน **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
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