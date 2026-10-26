---
title: ToChar()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แปลงสองไบต์จากอาเรย์ที่ระบุโดยเริ่มต้นที่ดัชนีที่กำหนดเป็นค่า char_t
type: docs
weight: 40
url: /th/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) เมธอด

แปลงสองไบต์จากอาเรย์ที่ระบุ เริ่มต้นที่ดัชนีที่ระบุเป็นค่า char_t

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### อากิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์เพื่อแปลง |
| startIndex | int | [Index](../../index/) ในอาเรย์ที่ต้องเริ่มรับไบต์สำหรับการแปลง |

### ค่าที่ส่งกลับ

ค่า char_t ที่ได้จากการแปลง

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) เมธอด

แปลงสองไบต์จากอาเรย์ที่ระบุ เริ่มต้นที่ดัชนีที่ระบุเป็นค่า char_t

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### อากิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ที่มีไบต์เพื่อแปลง |
| startIndex | int | [Index](../../index/) ในอาเรย์ที่ต้องเริ่มรับไบต์สำหรับการแปลง |

### ค่าที่ส่งกลับ

ค่า char_t ที่ได้จากการแปลง

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [BitConverter](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)