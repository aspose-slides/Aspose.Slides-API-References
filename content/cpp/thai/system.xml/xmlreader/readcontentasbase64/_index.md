---
title: ReadContentAsBase64()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: อ่านเนื้อหาและส่งคืนไบต์ไบนารีที่ถอดรหัส Base64
type: docs
weight: 755
url: /th/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด

อ่านเนื้อหาและส่งคืนไบต์ไบนารีที่ถอดรหัส Base64

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่จะคัดลอกข้อความผลลัพธ์เข้าไป ค่าไม่สามารถเป็น **nullptr** ได้ |
| index | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์ |
| count | **int32_t** | จำนวนไบต์สูงสุดที่จะคัดลอกเข้าไปในบัฟเฟอร์ จำนวนไบต์ที่คัดลอกจริงจะถูกส่งคืนจากเมธอดนี้ |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์

## ดูเพิ่มเติม

* ประเภทนิยาม [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)