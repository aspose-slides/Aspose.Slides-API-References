---
title: ReadContentAsBinHex()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัส BinHex
type: docs
weight: 599
url: /th/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด

อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัส BinHex

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์ไปยังบัฟเฟอร์นี้ ค่าไม่สามารถเป็น **nullptr**. |
| index | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์. |
| count | **int32_t** | จำนวนไบต์สูงสุดที่จะคัดลอกไปยังบัฟเฟอร์ จำนวนไบต์ที่คัดลอกจริงจะถูกส่งคืนจากเมธอดนี้. |

### ค่าที่ส่งคืน

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)