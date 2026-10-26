---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: สร้าง audio frame ใหม่ที่เชื่อมโยงกับไฟล์ audio ภายนอกและแทรกลงใน shape collection ที่ตำแหน่งที่ระบุ
type: docs
weight: 235
url: /th/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) เมธอด

สร้าง audio frame ใหม่ที่เชื่อมโยงกับไฟล์ audio ภายนอกและแทรกลงใน shape collection ที่ตำแหน่งที่ระบุ

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ซึ่งจะทำการแทรก audio frame |
| x | **float** | พิกัด x ของ audio frame ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ audio frame ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของ audio frame ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของ audio frame ใหม่, หน่วยเป็นจุด |
| fname | [System::String](../../../system/string/) | เส้นทางหรือชื่อของไฟล์ audio ภายนอกที่ต้องการเชื่อมโยง |

### Return Value

ออบเจ็กต์ [IAudioFrame](../../iaudioframe/) ที่สร้างใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudioFrame](../../iaudioframe/)
* คลาส [String](../../../system/string/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)