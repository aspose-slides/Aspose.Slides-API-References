---
title: ToUInt32()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงไบต์สี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มจากดัชนีที่กำหนดให้เป็นค่าตัวเลขเต็ม 32 บิตที่ไม่มีเครื่องหมาย
type: docs
weight: 105
url: /th/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) เมธอด


Converts four bytes from the specified array starting at the specified index to unsigned 32-bit integer value.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์สำหรับแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่เริ่มนำไบต์มาสำหรับการแปลง |

### ค่าการคืนค่า

ค่าเต็ม 32 บิตที่ไม่มีเครื่องหมายที่ได้จากการแปลง

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) เมธอด


Converts four bytes from the specified array starting at the specified index to unsigned 32-bit integer value.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ที่มีไบต์สำหรับแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่เริ่มนำไบต์มาสำหรับการแปลง |

### ค่าการคืนค่า

ค่าเต็ม 32 บิตที่ไม่มีเครื่องหมายที่ได้จากการแปลง

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [BitConverter](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)