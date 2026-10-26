---
title: set_VolumeValue()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตั้งค่าปริมาณเสียงเป็นเปอร์เซ็นต์. เขียน float.
type: docs
weight: 391
url: /th/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) เมธอด


ตั้งค่าความดังเสียงเป็นเปอร์เซ็นต์. เขียน **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งค่าระยะเวลา fade เริ่มต้นเป็น 200มิลลิวินาที
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)