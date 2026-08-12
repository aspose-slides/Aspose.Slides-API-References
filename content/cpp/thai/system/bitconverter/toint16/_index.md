---
title: ToInt16()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงไบต์สองไบต์จากแอร์เรย์ที่ระบุเริ่มจากดัชนีที่กำหนดเป็นค่าจำนวนเต็ม 16-bit
type: docs
weight: 53
url: /th/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) method

แปลงไบต์สองไบต์จากแอเรย์ที่ระบุเริ่มจากดัชนีที่กำหนดเป็นค่าจำนวนเต็ม 16-bit

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์เพื่อทำการแปลง |
| startIndex | int | [Index](../../index/) ในแอเรย์ที่เริ่มนำไบต์มาทำการแปลง |

### ค่าที่ส่งคืน

ค่าจำนวนเต็ม 16-bit ที่ได้จากการแปลง

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) method

แปลงไบต์สองไบต์จากแอเรย์ที่ระบุเริ่มจากดัชนีที่กำหนดเป็นค่าจำนวนเต็ม 16-bit

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ที่มีไบต์เพื่อทำการแปลง |
| startIndex | int | [Index](../../index/) ในแอเรย์ที่เริ่มนำไบต์มาทำการแปลง |

### ค่าที่ส่งคืน

ค่าจำนวนเต็ม 16-bit ที่ได้จากการแปลง

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)