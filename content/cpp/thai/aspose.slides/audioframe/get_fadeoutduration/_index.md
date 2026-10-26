---
title: get_FadeOutDuration()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุระยะเวลาที่ใช้สำหรับการหรี่เสียงออกของสื่อในขั้นสุดท้ายเป็นมิลลิวินาที อ่าน float.
type: docs
weight: 352
url: /th/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() เมธอด

ระบุระยะเวลาที่ใช้สำหรับการหรี่เสียงออกของสื่อในขั้นสุดท้ายเป็นมิลลิวินาที อ่าน **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งค่าระยะเวลาการหรี่เสียงออกในขั้นสุดท้ายเป็น 500มิลลิวินาที
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)