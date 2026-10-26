---
title: set_FadeOutDuration()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุระยะเวลาสำหรับการเฟดเอาต์สุดท้ายของสื่อเป็นมิลลิวินาที เขียนเป็น float.
type: docs
weight: 365
url: /th/aspose.slides/iaudioframe/set_fadeoutduration/
---
## IAudioFrame::set_FadeOutDuration(float) เมธอด


ระบุระยะเวลาในมิลลิวินาทีสำหรับการเฟดเอาต์สุดท้ายของสื่อ เขียนเป็น **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeOutDuration(float value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งค่าระยะเวลาการเฟดเอาต์สุดท้ายเป็น 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)