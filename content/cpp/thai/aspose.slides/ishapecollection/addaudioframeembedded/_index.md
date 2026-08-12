---
title: AddAudioFrameEmbedded()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างเฟรมเสียงใหม่ที่ฝังไฟล์ WAV และเพิ่มเข้าไปยังส่วนท้ายของคอลเลกชันรูปร่าง เสียงที่ฝังจะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios
type: docs
weight: 248
url: /th/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) เมธอด

สร้างเฟรมเสียงใหม่ที่ฝังไฟล์ WAV และเพิ่มเข้าไปยังส่วนท้ายของคอลเลกชันรูปร่าง เสียงที่ฝังจะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุตที่มีข้อมูลเสียง WAV เพื่อฝัง |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IAudioFrame](../../iaudioframe/) ที่สร้างใหม่

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) เมธอด

สร้างเฟรมเสียงใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่างโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | อินสแตนซ์ [IAudio](../../iaudio/) จากคอลเลกชัน Presentation.Audios |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IAudioFrame](../../iaudioframe/) ที่สร้างใหม่

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [IShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)