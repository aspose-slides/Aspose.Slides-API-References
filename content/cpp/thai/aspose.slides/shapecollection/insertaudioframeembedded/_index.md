---
title: InsertAudioFrameEmbedded()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "สร้าง audio frame ใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และแทรกเข้าไปใน shape collection ที่ตำแหน่งที่ระบุ ส่วนเสียงที่ฝังถูกเพิ่มไปยังคอลเลกชัน Presentation::get_Audios"
type: docs
weight: 300
url: /th/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) เมธอด

สร้าง audio frame ใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และแทรกเข้าไปใน shape collection ที่ตำแหน่งที่ระบุ ด้านเสียงที่ฝังอยู่จะถูกเพิ่มไปยังคอลเลกชัน [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์สำหรับแทรก audio frame |
| x | **float** | พิกัด x ของ audio frame ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ audio frame ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของ audio frame ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของ audio frame ใหม่, หน่วยเป็นจุด |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุตที่บรรจุข้อมูลเสียง WAV เพื่อฝัง |

### ค่าที่ส่งกลับ

[IAudioFrame](../../iaudioframe/) ที่สร้างใหม่

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) เมธอด

สร้าง audio frame ใหม่และแทรกลงใน shape collection ที่ตำแหน่งที่กำหนดโดยใช้วัตถุ audio ที่มีอยู่จากรายการ [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์สำหรับแทรก audio frame |
| x | **float** | พิกัด x ของ audio frame ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ audio frame ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของ audio frame ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของ audio frame ใหม่, หน่วยเป็นจุด |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | อินสแตนซ์ของ [IAudio](../../iaudio/) จากคอลเลกชัน [Presentation::get_Audios](../../presentation/get_audios/) เพื่อฝัง |

### ค่าที่ส่งกลับ

[IAudioFrame](../../iaudioframe/) ที่สร้างใหม่

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudioFrame](../../iaudioframe/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [ShapeCollection](../)
* คลาส [IAudio](../../iaudio/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)