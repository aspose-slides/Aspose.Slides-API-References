---
title: set_VolumeValue()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ตั้งค่าปริมาณเสียงเป็นเปอร์เซ็นต์ เขียน float.
type: docs
weight: 391
url: /th/aspose.slides/iaudioframe/set_volumevalue/
---
## IAudioFrame::set_VolumeValue(float) เมธอด


ตั้งค่าปริมาณเสียงเป็นเปอร์เซ็นต์ เขียน **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_VolumeValue(float value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่มเฟรมเสียง
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)