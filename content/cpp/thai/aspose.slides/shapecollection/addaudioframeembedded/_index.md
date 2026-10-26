---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ฝังไว้และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปแบบ เสียงที่ฝังไว้จะถูกเพิ่มไปยังคอลเลกชัน Presentation::get_Audios"
type: docs
weight: 287
url: /th/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method

Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. The embedded audio is added to the [Presentation::get_Audios](../../presentation/get_audios/) collection.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นจุด |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุตที่มีข้อมูล WAV เพื่อฝัง |

### ค่าที่ส่งคืน

[IAudioFrame](../../iaudioframe/) ที่ถูกสร้างใหม่.

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีสร้าง [Audio](../../audio/) Frame. 
```cpp
// สร้างอ็อบเจ็กต์ของคลาส Presentation ที่แสดงไฟล์การนำเสนอ
auto pres = System::MakeObject<Presentation>();

// ดึงสไลด์แรก
auto slide = pres->get_Slides()->idx_get(0);
// โหลดไฟล์เสียง wav ไปยังสตรีม
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// เพิ่ม Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// ตั้งค่าโหมดการเล่นและระดับเสียงของ Audio
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// บันทึกไฟล์ PowerPoint ลงดิสก์
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method

Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the [Presentation::get_Audios](../../presentation/get_audios/) list.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นจุด |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | อินสแตนซ์ [IAudio](../../iaudio/) จากคอลเลกชัน [Presentation::get_Audios](../../presentation/get_audios/) |

### ค่าที่ส่งคืน

[IAudioFrame](../../iaudioframe/) ที่ถูกสร้างใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)