---
title: get_RewindAudio()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าการเล่นเสียงจะถูกรวินด์อัตโนมัติไปที่จุดเริ่มต้นหลังจากการเล่นหรือไม่ อ่าน bool.
type: docs
weight: 235
url: /th/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() เมธอด


กำหนดว่าเสียงจะถูกรีวินด์อัตโนมัติไปที่จุดเริ่มต้นหลังจากการเล่นหรือไม่ อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// เพิ่มเฟรมเสียง
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ตั้งค่า Audio ให้เล่นต่อเนื่องทั่วสไลด์
audioFrame->set_PlayAcrossSlides(true);

// ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปที่จุดเริ่มต้นหลังจากเล่น
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)