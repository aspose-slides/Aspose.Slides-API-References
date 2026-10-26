---
title: ToBoolean()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: แปลงไบต์หนึ่งจากอาร์เรย์ที่ระบุโดยเริ่มจากตำแหน่งที่ระบุเป็นค่า boolean.
type: docs
weight: 27
url: /th/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) method

แปลงไบต์หนึ่งจากอาร์เรย์ที่ระบุโดยเริ่มจากดัชนีที่ระบุเป็นค่า boolean.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์สำหรับการแปลง |
| startIndex | int | [Index](../../index/) ตำแหน่งเริ่มต้นในอาร์เรย์ที่ใช้เริ่มดึงไบต์สำหรับการแปลง |

### ค่าที่คืน

[Boolean](../../boolean/) ค่าที่ได้จากการแปลง

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) method

แปลงไบต์หนึ่งจากอาร์เรย์ที่ระบุโดยเริ่มจากดัชนีที่ระบุเป็นค่า boolean.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ที่มีไบต์สำหรับการแปลง |
| startIndex | int | [Index](../../index/) ตำแหน่งเริ่มต้นในอาร์เรย์ที่ใช้เริ่มดึงไบต์สำหรับการแปลง |

### ค่าที่คืน

[Boolean](../../boolean/) ค่าที่ได้จากการแปลง

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [BitConverter](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)