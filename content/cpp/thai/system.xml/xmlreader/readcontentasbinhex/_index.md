---
title: ReadContentAsBinHex()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสเป็น BinHex.
type: docs
weight: 781
url: /th/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด


อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสเป็น **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความที่ได้ผลลัพธ์ ค่านี้ไม่สามารถเป็น **nullptr** |
| index | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์ |
| count | **int32_t** | จำนวนไบต์สูงสุดที่จะคัดลอกเข้าไปในบัฟเฟอร์ จำนวนไบต์ที่คัดลอกจริงจะถูกส่งกลับจากเมธอดนี้ |

### ค่าที่คืน

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)