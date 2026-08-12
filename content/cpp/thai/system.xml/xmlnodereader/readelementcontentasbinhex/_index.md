---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: อ่านองค์ประกอบและถอดรหัสเนื้อหา BinHex.
type: docs
weight: 482
url: /th/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) เมธอด


อ่านองค์ประกอบและถอดรหัสเนื้อหา BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ใช้คัดลอกข้อความผลลัพธ์เข้าไป. ค่านี้ไม่สามารถเป็น **nullptr**. |
| index | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ที่เริ่มคัดลอกผลลัพธ์. |
| count | **int32_t** | จำนวนไบต์สูงสุดที่จะคัดลอกเข้าไปในบัฟเฟอร์. จำนวนไบต์ที่คัดลอกจริงจะถูกส่งคืนจากเมธอดนี้. |

### ค่าที่คืน

จำนวนไบต์ที่เขียนเข้าไปในบัฟเฟอร์.

## ดูเพิ่มเติม

* กำหนดชนิด [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlNodeReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)