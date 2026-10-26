---
title: FromBase64CharArray()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ถอดรหัสข้อมูลที่เข้ารหัสแบบ base-64 ซึ่งแสดงเป็นช่วงในอาร์เรย์ของอักขระ Unicode.
type: docs
weight: 53
url: /th/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) เมธอด


ถอดรหัสข้อมูลที่เข้ารหัสแบบ base-64 ซึ่งแสดงเป็นช่วงในอาร์เรย์ของอักขระ Unicode.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | อาร์เรย์ที่มีข้อมูลเพื่อถอดรหัส |
| offset | int | ตำแหน่งในอาร์เรย์อินพุตที่ช่วงที่จะถอดรหัสเริ่มต้น |
| length | int | ความยาวของช่วงที่จะถอดรหัส |

### ค่าที่คืนกลับ

อาร์เรย์ของไบต์ที่บรรจุข้อมูลที่ถอดรหัสแล้ว

## ดูเพิ่มเติม

* กำหนดชนิด [ArrayPtr](../../arrayptr/)
* โครงสร้าง [Convert](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)