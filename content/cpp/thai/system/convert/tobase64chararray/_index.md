---
title: ToBase64CharArray()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: Base-64 จะทำการเข้ารหัสช่วงขององค์ประกอบในอาร์เรย์ไบต์ที่ระบุและจัดเก็บข้อมูลที่เข้ารหัสเป็นอาร์เรย์ของอักขระ Unicode.
type: docs
weight: 27
url: /th/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) เมธอด


Base-64 encodes a range of elements in the specified byte array and stores the encoded data as an array of Unicode characters.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ของไบต์ที่มีช่วงขององค์ประกอบเพื่อเข้ารหัส |
| offset_in | int | ดัชนีขององค์ประกอบในอาร์เรย์อินพุตที่ช่วงที่จะเข้ารหัสเริ่มต้น |
| length | int | ความยาวของช่วงขององค์ประกอบที่จะเข้ารหัส |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | การอ้างอิงคงที่ไปยังอาร์เรย์เอาต์พุตที่ผลลัพธ์จะถูกวาง |
| offset_out | int | ดัชนีในอาร์เรย์เอาต์พุตที่เริ่มวางผลลัพธ์ |
| insert_line_breaks | **bool** | ระบุว่าจะใส่ตัวอักษรขึ้นบรรทัดใหม่ในอาร์เรย์เอาต์พุตหลังจากแต่ละ 76 base-64 ตัวอักษรหรือไม่ |

### ค่าที่คืน

จำนวนตัวอักษรที่เขียนลงในอาร์เรย์เอาต์พุต

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) เมธอด


Base-64 encodes a range of elements in the specified byte array and stores the encoded data as an array of Unicode characters.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ของไบต์ที่มีช่วงขององค์ประกอบเพื่อเข้ารหัส |
| offset_in | int | ดัชนีขององค์ประกอบในอาร์เรย์อินพุตที่ช่วงที่จะเข้ารหัสเริ่มต้น |
| length | int | ความยาวของช่วงขององค์ประกอบที่จะเข้ารหัส |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | การอ้างอิงคงที่ไปยังอาร์เรย์เอาต์พุตที่ผลลัพธ์จะถูกวาง |
| offset_out | int | ดัชนีในอาร์เรย์เอาต์พุตที่เริ่มวางผลลัพธ์ |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | ระบุตัวเลือกการจัดรูปแบบของข้อมูลที่เข้ารหัสด้วย base-64 |

### ค่าที่คืน

จำนวนตัวอักษรที่เขียนลงในอาร์เรย์เอาต์พุต

## ดูเพิ่มเติม

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)