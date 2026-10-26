---
title: set_TrimFromStart()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุระยะเวลาเป็นมิลลิวินาทีที่ต้องลบออกจากจุดเริ่มต้นของสื่อระหว่างการเล่น เขียนเป็น float.
type: docs
weight: 417
url: /th/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) เมธอด

ระบุช่วงเวลาในมิลลิวินาทีที่ต้องลบออกจากจุดเริ่มต้นของสื่อระหว่างการเล่น เขียนเป็น **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งค่าเวลาเริ่มต้นที่ต้องตัด 1.5 วินาที
audioFrame->set_TrimFromStart(1500.0f);
```

## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)