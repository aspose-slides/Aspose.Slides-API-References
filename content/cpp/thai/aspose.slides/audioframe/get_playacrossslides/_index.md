---
title: get_PlayAcrossSlides()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าการเล่นเสียงดำเนินต่อข้ามสไลด์หรือไม่ อ่าน bool.
type: docs
weight: 209
url: /th/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() เมธอด


กำหนดว่าการเล่นเสียงดำเนินต่อข้ามสไลด์หรือไม่ อ่าน **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// เพิ่ม Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ตั้งค่า Audio ให้เล่นต่อข้ามสไลด์
audioFrame->set_PlayAcrossSlides(true);

// ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากเล่น
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)