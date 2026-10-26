---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: อ่านองค์ประกอบและถอดรหัสเนื้อหา Base64.
type: docs
weight: 469
url: /th/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


อ่านองค์ประกอบและถอดรหัสเนื้อหา Base64.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่จะคัดลอกข้อความผลลัพธ์ ค่าไม่สามารถเป็น **nullptr** ได้. |
| index | **int32_t** | ออฟเซ็ตภายในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์. |
| count | **int32_t** | จำนวนไบต์สูงสุดที่คัดลอกเข้าไปในบัฟเฟอร์ จำนวนไบต์ที่คัดลอกจริงจะถูกส่งกลับจากเมธอดนี้. |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)