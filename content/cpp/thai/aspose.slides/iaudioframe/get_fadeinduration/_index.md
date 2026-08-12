---
title: get_FadeInDuration()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ระบุระยะเวลาการเฟดอินเริ่มต้นของสื่อเป็นมิลลิวินาที อ่าน float.
type: docs
weight: 326
url: /th/aspose.slides/iaudioframe/get_fadeinduration/
---
## IAudioFrame::get_FadeInDuration() เมธอด


ระบุระยะเวลาการเฟดอินเริ่มต้นของสื่อเป็นมิลลิวินาที อ่าน **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeInDuration()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// กำหนดระยะเวลาการเฟดอินเริ่มต้นเป็น 200 มิลลิวินาที
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมส페ซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)