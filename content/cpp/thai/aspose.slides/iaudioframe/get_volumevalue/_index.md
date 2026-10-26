---
title: get_VolumeValue()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนระดับเสียงของออดิโอเป็นเปอร์เซ็นต์ อ่าน float.
type: docs
weight: 378
url: /th/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() เมธอด

ส่งคืนระดับเสียงของออดิโอเป็นเปอร์เซ็นต์ อ่าน **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// เพิ่ม Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// ตั้งค่าระยะเวลา fade เริ่มต้นเป็น 200 มิลลิวินาที
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IAudioFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)