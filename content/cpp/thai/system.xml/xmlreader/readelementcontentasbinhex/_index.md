---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านองค์ประกอบและถอดรหัสเนื้อหา BinHex
type: docs
weight: 794
url: /th/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

อ่านองค์ประกอบและถอดรหัสเนื้อหา **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์นี้ ค่าไม่สามารถเป็น **nullptr** |
| index | **int32_t** | ตำแหน่งเริ่มต้นในบัฟเฟอร์ที่ใช้คัดลอกผลลัพธ์ |
| count | **int32_t** | จำนวนไบต์สูงสุดที่คัดลอกเข้าไปในบัฟเฟอร์ จำนวนไบต์ที่คัดลอกจริงจะถูกส่งคืนจากเมธอดนี้ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์.

## ดูเพิ่มเติม

* ประเภทนิยาม [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)