---
title: set_TrimFromEnd()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุช่วงเวลา ที่จะถูกลบออกจากส่วนท้ายของสื่อระหว่างการเล่น, หน่วยเป็นมิลลิวินาที. เขียนเป็น float.
type: docs
weight: 443
url: /th/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) เมธอด


ระบุช่วงเวลา ที่จะถูกลบออกจากส่วนท้ายของสื่อระหว่างการเล่น, หน่วยเป็นมิลลิวินาที. เขียนเป็น **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the end trimming time 2 seconds
audioFrame->set_TrimFromEnd(2000.0f);
```

## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)