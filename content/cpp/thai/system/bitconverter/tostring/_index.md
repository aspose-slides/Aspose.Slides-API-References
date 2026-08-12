---
title: ToString()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงค่าทั้งหมดของอาเรย์ไบต์ที่ระบุให้เป็นสตริงรูปแบบฐานสิบหก. รูปแบบของตัวอักษรที่ใช้ในหมายเลขฐานสิบหกและตัวคั่นที่ใส่ระหว่างแต่ละคู่ของไบต์ที่อยู่ติดกันจะถูกกำหนดผ่านอาร์กิวเมนต์ที่สอดคล้องกัน.
type: docs
weight: 157
url: /th/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) เมธอด

แปลงค่าทั้งหมดของอาเรย์ไบต์ที่ระบุเป็นสตริงรูปแบบฐานสิบหก. รูปแบบของตัวอักษรที่ใช้ในหมายเลขฐานสิบหกและตัวคั่นที่ใส่ระหว่างแต่ละคู่ของไบต์ที่อยู่ติดกันจะถูกกำหนดผ่านอาร์กิวเมนต์ที่สอดคล้องกัน.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์สำหรับการแปลง |
| uppercase | **bool** | ระบุรูปแบบตัวอักษรที่ใช้ในผลลัพธ์รูปแบบฐานสิบหก |
| separator | const [String](../../string/)\& | สตริงที่ใช้เป็นตัวคั่นที่ใส่ระหว่างแต่ละคู่ของไบต์ที่อยู่ติดกันในสตริงผลลัพธ์ |

### ค่าที่คืนกลับ

[String](../../string/) ที่มีการแสดงผลรูปแบบฐานสิบหกของอาเรย์ไบต์ที่ระบุ

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) เมธอด

แปลงค่าของอาเรย์ไบต์ที่ระบุเป็นสตริงรูปแบบฐานสิบหกโดยเริ่มที่ดัชนีที่ระบุ.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์สำหรับการแปลง |
| startIndex | int | [Index](../../index/) ในอาเรย์ที่ระบุที่เริ่มทำการแปลง |

### ค่าที่คืนกลับ

[String](../../string/) ที่มีการแสดงผลรูปแบบฐานสิบหกของช่วงองค์ประกอบที่ระบุของอาเรย์ที่ระบุ

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) เมธอด

แปลงช่วงค่าของอาเรย์ไบต์ที่ระบุเป็นสตริงรูปแบบฐานสิบหก.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์สำหรับการแปลง |
| startIndex | int | [Index](../../index/) ในอาเรย์ที่ระบุที่ช่วงขององค์ประกอบอาเรย์ไบต์ที่จะทำการแปลงเริ่มต้น |
| length | int | ความยาวของช่วงขององค์ประกอบอาเรย์ไบต์ที่จะทำการแปลง |

### ค่าที่คืนกลับ

[String](../../string/) ที่มีการแสดงผลรูปแบบฐานสิบหกของช่วงองค์ประกอบที่ระบุของอาเรย์ที่ระบุ

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [String](../../string/)
* คลาส [BitConverter](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)