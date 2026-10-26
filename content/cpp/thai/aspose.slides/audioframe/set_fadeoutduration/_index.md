---
title: set_FadeOutDuration()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุระยะเวลาในการจางเสียงสุดท้ายของสื่อเป็นมิลลิวินาที. เขียนเป็น float.
type: docs
weight: 365
url: /th/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) เมธอด


ระบุระยะเวลาของการจางเสียงสุดท้ายของสื่อเป็นมิลลิวินาที. เขียนเป็น **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// กำหนดระยะเวลาการจางเสียงสุดท้ายเป็น 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)