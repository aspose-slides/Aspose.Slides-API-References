---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: อ่านองค์ประกอบและถอดรหัสเนื้อหา Base64.
type: docs
weight: 586
url: /th/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด

อ่านองค์ประกอบและถอดรหัสเนื้อหา Base64

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความที่ได้ ผลลัพธ์นี้ไม่สามารถเป็น **nullptr** ได้ |
| index | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์ |
| count | **int32_t** | จำนวนไบต์สูงสุดที่คัดลอกเข้าไปในบัฟเฟอร์ จำนวนไบต์ที่คัดลอกจริงจะถูกส่งกลับจากเมธอดนี้ |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)