---
title: ReadContentAsBinHex()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก BinHex
type: docs
weight: 456
url: /th/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด

อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก BinHex

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์ ค่านี้ไม่สามารถเป็น **nullptr** |
| index | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์ |
| count | **int32_t** | จำนวนไบต์สูงสุดที่จะคัดลอกเข้าไปในบัฟเฟอร์ จำนวนไบต์ที่ถูกคัดลอกจริงจะถูกส่งคืนจากเมธอดนี้ |

### Return Value

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlNodeReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)