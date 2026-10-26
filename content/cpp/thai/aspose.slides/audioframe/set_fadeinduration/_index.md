---
title: set_FadeInDuration()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุระยะเวลาเป็นมิลลิวินาทีสำหรับการเฟดอินเริ่มต้นของสื่อ เขียนเป็น float.
type: docs
weight: 339
url: /th/aspose.slides/audioframe/set_fadeinduration/
---
## AudioFrame::set_FadeInDuration(float) เมธอด


ระบุระยะเวลาเป็นมิลลิวินาทีสำหรับการเฟดอินเริ่มต้นของสื่อ เขียนเป็น **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeInDuration(float value) override
```

## หมายเหตุ


ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งค่าระยะเวลาการเฟดอินเริ่มต้นเป็น 200 มิลลิวินาที
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)