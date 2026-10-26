---
title: GetObjectStoringLocation()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าต้องจัดเก็บอ็อบเจกต์ไว้ที่ไหน เมธอดนี้ถูกเรียกหนึ่งครั้งต่อแต่ละ id ของอ็อบเจกต์ ไม่ได้รับการรับประกันว่าจะไม่มีอ็อบเจกต์สองรายการที่มีข้อมูลเดียวกัน, semanticName และ contentType แต่มี id ที่แตกต่างกัน
type: docs
weight: 1
url: /th/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) method


กำหนดว่าต้องจัดเก็บอ็อบเจกต์ไว้ที่ไหน เมธอดนี้ถูกเรียกหนึ่งครั้งต่อแต่ละ id ของอ็อบเจกต์ ไม่ได้รับการรับประกันว่าจะไม่มีอ็อบเจกต์สองรายการที่มีข้อมูลเดียวกัน, semanticName และ contentType แต่มี id ที่แตกต่างกัน

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | **int32_t** | รหัสอ็อบเจกต์ รหัสนี้เป็นค่าที่ไม่ซ้ำกันทั่วทั้งการดำเนินการ |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลไบนารีของอ็อบเจกต์ พารามิเตอร์นี้อาจเป็นค่า null หากข้อมูลไบนารีของอ็อบเจกต์ยังไม่ได้สร้าง |
| semanticName | [System::String](../../../system/string/) | ข้อความสั้นบางส่วนอธิบายความหมายของอ็อบเจกต์ ตัวควบคุมอาจใช้ค่านี้เป็นส่วนหนึ่งของชื่ออ็อบเจกต์ภายนอก แต่ขึ้นอยู่กับผู้จัดส่งในการรับรองว่าชื่อจะไม่ซ้ำและมีเฉพาะอักขระที่อนุญาต |
| contentType | [System::String](../../../system/string/) | ชนิด MIME ของอ็อบเจกต์ |
| recomendedExtension | [System::String](../../../system/string/) | ส่วนขยายของชื่อไฟล์ที่แนะนำสำหรับ MIME type นี้ |

### Return Value

Decision

## See Also

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)