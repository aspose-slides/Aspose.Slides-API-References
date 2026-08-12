---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: อ่านองค์ประกอบและถอดรหัสเนื้อหา BinHex.
type: docs
weight: 612
url: /th/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด

อ่านองค์ประกอบและถอดรหัสเนื้อหา BinHex.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์นี้ ค่านี้ไม่สามารถเป็น **nullptr**. |
| index | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์. |
| count | **int32_t** | จำนวนไบต์สูงสุดที่จะคัดลอกเข้าสู่บัฟเฟอร์ จำนวนไบต์ที่คัดลอกจริงจะถูกส่งคืนจากเมธอดนี้. |

### ค่าที่ส่งคืน

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)