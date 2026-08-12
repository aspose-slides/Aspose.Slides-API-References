---
title: get_VolumeValue()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนระดับเสียงในหน่วยเปอร์เซ็นต์. อ่าน float.
type: docs
weight: 378
url: /th/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() เมธอด


ส่งคืนปริมาณเสียงในหน่วยเปอร์เซ็นต์. อ่าน **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งค่าระยะเวลา fade เริ่มต้นเป็น 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [AudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)