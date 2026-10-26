---
title: set_TrimFromEnd()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ระบุช่วงเวลาโดยหน่วยมิลลิวินาทีที่ต้องการลบออกจากส่วนท้ายของสื่อระหว่างการเล่น. เขียน float.
type: docs
weight: 443
url: /th/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) เมธอด

ระบุระยะเวลาที่จะถูกลบออกจากส่วนท้ายของสื่อขณะเล่น, หน่วยเป็นมิลลิวินาที. เขียน **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งเวลา trim จากส่วนท้ายเป็น 2 วินาที
audioFrame->set_TrimFromEnd(2000.0f);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)