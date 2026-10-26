---
title: ReadContentAsBase64()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก Base64.
type: docs
weight: 638
url: /th/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก **Base64**.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์นี้ ค่านี้ไม่สามารถเป็น **nullptr** ได้ |
| index | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์ |
| count | **int32_t** | จำนวนไบต์สูงสุดที่จะคัดลอกไปยังบัฟเฟอร์ จำนวนไบต์ที่แท้จริงที่คัดลอกได้จะถูกคืนจากเมธอดนี้ |

### ค่าที่คืน

จำนวนไบต์ที่เขียนลงบัฟเฟอร์.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlTextReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)