---
title: ReadContentAsBase64()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: อ่านเนื้อหาและส่งคืนไบต์ไบนารีที่ถอดรหัส Base64
type: docs
weight: 573
url: /th/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด

อ่านเนื้อหาและส่งคืนไบต์ไบนารีที่ถอดรหัส Base64

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์. ค่านี้ไม่สามารถเป็น **nullptr**. |
| index | **int32_t** | ออฟเซ็ทในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์. |
| count | **int32_t** | จำนวนไบต์สูงสุดที่คัดลอกลงในบัฟเฟอร์. จำนวนไบต์ที่คัดลอกจริงจะถูกส่งกลับจากเมธอดนี้. |

### Return Value

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์.

## ดูเพิ่มเติม

* ชนิดนิยาม [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)