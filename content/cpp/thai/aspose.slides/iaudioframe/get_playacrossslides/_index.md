---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าเสียงจะเล่นต่อเนื่องข้ามสไลด์หรือไม่. อ่าน bool.
type: docs
weight: 209
url: /th/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() เมธอด


กำหนดว่าเสียงจะเล่นต่อเนื่องข้ามสไลด์หรือไม่. อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// เพิ่ม Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ตั้งค่า Audio ให้เล่นต่อเนื่องข้ามสไลด์
audioFrame->set_PlayAcrossSlides(true);

// ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังการเล่น
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)