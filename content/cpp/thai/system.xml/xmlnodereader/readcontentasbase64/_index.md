---
title: ReadContentAsBase64()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสเป็น Base64
type: docs
weight: 443
url: /th/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด

อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสเป็น Base64 แล้ว

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์เข้าไป ค่า này ไม่สามารถเป็น **nullptr** ได้ |
| index | **int32_t** | ตำแหน่งออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์ |
| count | **int32_t** | จำนวนไบต์สูงสุดที่จะคัดลอกเข้าไปในบัฟเฟอร์ จำนวนไบต์ที่แท้จริงที่ถูกคัดลอกจะถูกคืนค่าจากเมธอดนี้ |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlNodeReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)