---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าการเล่นเสียงข้ามสไลด์หรือไม่ เขียน bool.
type: docs
weight: 222
url: /th/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) เมธอด


กำหนดว่าการเล่นเสียงข้ามสไลด์หรือไม่ เขียน **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// เพิ่ม Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ตั้งค่า Audio ให้เล่นข้ามสไลด์
audioFrame->set_PlayAcrossSlides(true);

// ตั้งค่า Audio ให้รีแวนด์อัตโนมัติไปจุดเริ่มต้นหลังจากเล่นเสร็จ
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)