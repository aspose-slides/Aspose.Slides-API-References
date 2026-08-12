---
title: get_FadeOutDuration()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุระยะเวลาเป็นมิลลิวินาทีสำหรับการหดเสียง fade-out สุดท้ายของสื่อ. อ่าน float.
type: docs
weight: 352
url: /th/aspose.slides/iaudioframe/get_fadeoutduration/
---
## IAudioFrame::get_FadeOutDuration() เมธอด


ระบุระยะเวลาเป็นมิลลิวินาทีสำหรับการหดเสียง fade-out สุดท้ายของสื่อ. อ่าน **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeOutDuration()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่มเฟรมเสียง
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// กำหนดระยะเวลา fade-out สุดท้ายเป็น 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)