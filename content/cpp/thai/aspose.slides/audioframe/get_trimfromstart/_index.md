---
title: get_TrimFromStart()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุระยะเวลาที่จะถูกลบออกจากจุดเริ่มต้นของสื่อระหว่างการเล่น, หน่วยเป็นมิลลิวินาที อ่าน float.
type: docs
weight: 404
url: /th/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() method

ระบุระยะเวลาที่จะถูกลบออกจากจุดเริ่มต้นของสื่อระหว่างการเล่น, หน่วยเป็นมิลลิวินาที อ่าน **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// กำหนดเวลาเริ่มต้นของการตัด 1.5 วินาที
audioFrame->set_TrimFromStart(1500.0f);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)