---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านอิลิเมนต์และถอดรหัสเนื้อหา BinHex.
type: docs
weight: 677
url: /th/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด

อ่านอิลิเมนต์และถอดรหัสเนื้อหา **BinHex**.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์นี้ ค่าไม่สามารถเป็น **nullptr** |
| index | **int32_t** | การออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์ |
| count | **int32_t** | จำนวนไบต์สูงสุดที่คัดลอกไปยังบัฟเฟอร์ จำนวนไบต์ที่คัดลอกจริงจะถูกส่งกลับจากเมธอดนี้ |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)