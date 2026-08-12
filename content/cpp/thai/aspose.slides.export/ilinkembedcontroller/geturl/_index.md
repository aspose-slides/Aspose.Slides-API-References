---
title: GetUrl()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ส่งคืน URL ไปยังอ็อบเจ็กต์ภายนอก เมธอดนี้จะถูกเรียกเสมอหาก ILinkEmbedController::GetObjectStoringLocation คืนค่า LinkEmbedDecision::Link และอาจถูกเรียกหาก ILinkEmbedController::GetObjectStoringLocation คืนค่า LinkEmbedDecision::Embed แต่การฝังเป็นไปไม่ได้ สามารถเรียกได้หลายครั้งสำหรับ id ของอ็อบเจ็กต์เดียวกัน"
type: docs
weight: 14
url: /th/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) เมธอด


ส่งคืน URL ไปยังอ็อบเจ็กต์ภายนอก เมธอดนี้จะถูกเรียกเสมอหาก [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) คืนค่า [LinkEmbedDecision::Link](../../linkembeddecision/) และอาจถูกเรียกหาก [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) คืนค่า [LinkEmbedDecision::Embed](../../linkembeddecision/) แต่การฝังไม่สามารถทำได้ สามารถเรียกได้หลายครั้งสำหรับ id ของอ็อบเจ็กต์เดียวกัน

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| id | **int32_t** | รหัสอ็อบเจ็กต์ รหัสนี้เป็นรหัสที่เป็นเอกลักษณ์ทั่วทั้งการดำเนินการ |
| referrer | **int32_t** | รหัสของอ็อบเจ็กต์อ้างอิง หรือ 0 หากอ็อบเจ็กต์ถูกอ้างอิงโดยเอกสารราก อาจใช้ในการสร้างลิงก์สัมพันธ์ |

### ค่าที่คืนกลับ

URL ของอ็อบเจ็กต์ภายนอกหรือ null หากควรละเว้นอ็อบเจ็กต์นี้

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [ILinkEmbedController](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)