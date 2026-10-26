---
title: get_TrimFromStart()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุระยะเวลาในหน่วยมิลลิวินาทีที่ต้องลบออกจากจุดเริ่มต้นของสื่อระหว่างการเล่น อ่าน float.
type: docs
weight: 404
url: /th/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() เมธอด

กำหนดระยะเวลาที่จะถูกลบออกจากจุดเริ่มต้นของสื่อระหว่างการเล่นเป็นมิลลิวินาที อ่าน **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งเวลาตัดเริ่มต้น 1.5 วินาที
audioFrame->set_TrimFromStart(1500.0f);
```

## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)