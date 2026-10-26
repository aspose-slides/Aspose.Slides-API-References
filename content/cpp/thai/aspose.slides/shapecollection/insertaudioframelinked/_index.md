---
title: InsertAudioFrameLinked()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและแทรกเข้าไปในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ
type: docs
weight: 274
url: /th/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) เมธอด


สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและแทรกเข้าไปในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจาก 0 ที่จะใส่เฟรมเสียงเข้าไป |
| x | **float** | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| fname | [System::String](../../../system/string/) | เส้นทางหรือชื่อไฟล์เสียงภายนอกที่ต้องการเชื่อมโยง |

### Return Value

อ็อบเจกต์ [IAudioFrame](../../iaudioframe/) ที่สร้างใหม่

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudioFrame](../../iaudioframe/)
* คลาส [String](../../../system/string/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)