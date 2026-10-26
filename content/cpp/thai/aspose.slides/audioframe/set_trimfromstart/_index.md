---
title: set_TrimFromStart()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุระยะเวลาที่ต้องตัดออกจากจุดเริ่มต้นของสื่อระหว่างการเล่นเป็นมิลลิวินาที เขียนเป็น float.
type: docs
weight: 417
url: /th/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) เมธอด


ระบุระยะเวลาที่ต้องตัดออกจากจุดเริ่มต้นของสื่อระหว่างการเล่นเป็นมิลลิวินาที เขียนเป็น **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งเวลาเริ่มตัด 1.5 วินาที
audioFrame->set_TrimFromStart(1500.0f);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)