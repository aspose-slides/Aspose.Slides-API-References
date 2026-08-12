---
title: get_TrimFromEnd()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ระบุระยะเวลาที่ต้องลบออกจากส่วนท้ายของสื่อระหว่างการเล่น, หน่วยเป็นมิลลิวินาที. อ่าน float.
type: docs
weight: 430
url: /th/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() เมธอด


ระบุระยะเวลาที่ต้องลบออกจากส่วนท้ายของสื่อระหว่างการเล่น, หน่วยเป็นมิลลิวินาที. อ่าน **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## หมายเหตุ


ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งค่าการตัดส่วนท้ายเป็น 2 วินาที
audioFrame->set_TrimFromEnd(2000.0f);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)