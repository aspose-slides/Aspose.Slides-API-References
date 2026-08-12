---
title: ReadElementContentAsBase64()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ่านองค์ประกอบและถอดรหัสเนื้อหา Base64.
type: docs
weight: 768
url: /th/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด


อ่านองค์ประกอบและถอดรหัสเนื้อหาที่เป็น **Base64**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความที่ได้ผลลัพธ์นี้ ค่านี้ไม่สามารถเป็น **nullptr** ได้ |
| index | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์ |
| count | **int32_t** | จำนวนไบต์สูงสุดที่คัดลอกไปยังบัฟเฟอร์ จำนวนไบต์ที่คัดลอกจริงจะถูกส่งกลับจากเมธอดนี้ |

### ค่าที่คืน

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)