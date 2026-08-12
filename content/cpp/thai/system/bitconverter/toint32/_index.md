---
title: ToInt32()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มจากดัชนีที่ระบุเป็นค่าเต็ม 32 บิต
type: docs
weight: 66
url: /th/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) เมธอด


แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มจากดัชนีที่ระบุเป็นค่าเต็ม 32 บิต

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### พารามิเตอร์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์เพื่อแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่ใช้เริ่มดึงไบต์สำหรับการแปลง |

### ค่าที่ส่งคืน

ค่าเต็ม 32 บิตที่ได้จากการแปลง

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) เมธอด


แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มจากดัชนีที่ระบุเป็นค่าเต็ม 32 บิต

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### พารามิเตอร์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ที่มีไบต์เพื่อแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่ใช้เริ่มดึงไบต์สำหรับการแปลง |

### ค่าที่ส่งคืน

ค่าเต็ม 32 บิตที่ได้จากการแปลง

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [BitConverter](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)