---
title: get_TrimFromEnd()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุระยะเวลาในหน่วยมิลลิวินาทีที่ต้องการลบออกจากส่วนท้ายของสื่อระหว่างการเล่น. อ่าน float.
type: docs
weight: 430
url: /th/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() เมธอด

ระบุระยะเวลาที่จะถูกลบออกจากส่วนท้ายของสื่อระหว่างการเล่น, หน่วยเป็นมิลลิวินาที. อ่าน **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งค่าการตัดจากส่วนท้ายเป็น 2 วินาที
audioFrame->set_TrimFromEnd(2000.0f);
```

## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)