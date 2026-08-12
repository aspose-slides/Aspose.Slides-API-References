---
title: set_RewindAudio()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: กำหนดว่าการเล่นเสียงจะถูกรีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากการเล่นหรือไม่ เขียนเป็น bool.
type: docs
weight: 248
url: /th/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) เมธอด

กำหนดว่าการเล่นเสียงจะถูกรีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากการเล่นหรือไม่ เขียนเป็น **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// เพิ่ม Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// ตั้งค่า Audio ให้เล่นต่อเนื่องบนสไลด์ทั้งหมด
audioFrame->set_PlayAcrossSlides(true);

// ตั้งค่า Audio ให้รีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังจากการเล่น
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)