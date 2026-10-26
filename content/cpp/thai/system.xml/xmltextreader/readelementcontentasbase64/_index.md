---
title: ReadElementContentAsBase64()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ่านองค์ประกอบและถอดรหัสเนื้อหา Base64.
type: docs
weight: 651
url: /th/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด


อ่านองค์ประกอบและถอดรหัสเนื้อหา Base64.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์เข้าไป. ค่านี้ไม่สามารถเป็น **nullptr** ได้. |
| index | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์. |
| count | **int32_t** | จำนวนไบต์สูงสุดที่คัดลอกเข้าไปในบัฟเฟอร์. จำนวนไบต์ที่คัดลอกจริงจะถูกส่งคืนจากเมธอดนี้. |

### ค่าที่ส่งคืน

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlTextReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)