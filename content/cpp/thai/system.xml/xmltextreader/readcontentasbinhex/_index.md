---
title: ReadContentAsBinHex()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก BinHex.
type: docs
weight: 664
url: /th/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก **BinHex**.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์ ค่านี้ต้องไม่เป็น **nullptr**. |
| index | **int32_t** | ตำแหน่งออฟเซตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์. |
| count | **int32_t** | จำนวนไบต์สูงสุดที่จะคัดลอกเข้าในบัฟเฟอร์ จำนวนไบต์ที่คัดลอกจริงจะถูกส่งคืนจากเมธอดนี้. |

### ค่าที่คืน

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)