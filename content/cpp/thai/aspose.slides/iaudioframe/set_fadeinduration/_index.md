---
title: set_FadeInDuration()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ระบุระยะเวลาการเฟดอินเริ่มต้นของสื่อเป็นมิลลิวินาที เขียนเป็น float.
type: docs
weight: 339
url: /th/aspose.slides/iaudioframe/set_fadeinduration/
---
## IAudioFrame::set_FadeInDuration(float) เมธอด


ระบุระยะเวลาในการเฟดอินเริ่มต้นของสื่อเป็นมิลลิวินาที เขียนเป็น **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeInDuration(float value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งค่าระยะเวลาเฟดอินเริ่มต้นเป็น 200 มิลลิวินาที
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)