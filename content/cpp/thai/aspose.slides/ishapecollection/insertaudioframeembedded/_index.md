---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และแทรกลงในคอลเลกชันรูปแบบที่ตำแหน่งที่ระบุ ไฟล์เสียงที่ฝังจะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios
type: docs
weight: 261
url: /th/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method

สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และแทรกลงในคอลเลกชันรูปแบบที่ตำแหน่งที่กำหนด ไฟล์เสียงที่ฝังอยู่จะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ใช้ในการแทรกเฟรมเสียง |
| x | **float** | ค่าพิกัด x ของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| y | **float** | ค่าพิกัด y ของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุตที่มีข้อมูลเสียง WAV เพื่อฝัง |

### Return Value

อ็อบเจ็กต์ [IAudioFrame](../../iaudioframe/) ที่สร้างใหม่

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) method

สร้างเฟรมเสียงใหม่และแทรกลงในคอลเลกชันรูปแบบที่ตำแหน่งที่กำหนดโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ใช้ในการแทรกเฟรมเสียง |
| x | **float** | ค่าพิกัด x ของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| y | **float** | ค่าพิกัด y ของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของเฟรมเสียงใหม่ หน่วยเป็นพอยต์ |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | อินสแตนซ์ [IAudio](../../iaudio/) จากคอลเลกชัน Presentation.Audios เพื่อฝัง |

### Return Value

อ็อบเจ็กต์ [IAudioFrame](../../iaudioframe/) ที่สร้างใหม่

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudioFrame](../../iaudioframe/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [IShapeCollection](../)
* คลาส [IAudio](../../iaudio/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)