---
title: ReadBinHex()
second_title: Aspose.Slides สำหรับ C++ เอกสารอธิบาย API
description: ถอดรหัส BinHex และคืนค่าไบต์ไบนารีที่ถอดรหัสแล้ว.
type: docs
weight: 781
url: /th/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

ถอดรหัส **BinHex** และคืนค่าไบต์ไบนารีที่ถอดรหัสแล้ว.

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์ที่ทำหน้าที่เป็นบัฟเฟอร์ซึ่งไบต์ไบนารีที่ถอดรหัสแล้วจะถูกเขียนไป |
| offset | **int32_t** | ดัชนีเริ่มจากศูนย์ในอาร์เรย์ที่ระบุว่ามิธอดสามารถเริ่มเขียนไปยังบัฟเฟอร์ได้จากตำแหน่งใด |
| len | **int32_t** | จำนวนไบต์ที่ต้องเขียนลงในบัฟเฟอร์ |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียนลงในบัฟเฟอร์ของคุณ.

## ดูเพิ่มเติม

* กำหนดชนิด [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlTextReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)