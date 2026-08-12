---
title: get_FadeInDuration()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุระยะเวลาเป็นมิลลิวินาทีสำหรับการเฟดอินเริ่มต้นของสื่อ. อ่าน float.
type: docs
weight: 326
url: /th/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() เมธอด

ระบุระยะเวลาเป็นมิลลิวินาทีสำหรับการเฟดอินเริ่มต้นของสื่อ. อ่าน **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)