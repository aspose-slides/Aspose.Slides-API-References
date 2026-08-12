---
title: ToBase64String()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: Base-64 เข้ารหัสองค์ประกอบในอาร์เรย์ไบต์ที่ระบุและส่งคืนข้อมูลที่เข้ารหัสเป็นสตริง.
type: docs
weight: 40
url: /th/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) เมธอด

Base-64 เข้ารหัสองค์ประกอบในอาร์เรย์ไบต์ที่ระบุและส่งคืนข้อมูลที่เข้ารหัสเป็นสตริง.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ของไบต์เพื่อเข้ารหัส |
| insert_line_breaks | **bool** | ระบุว่าต้องใส่อักขระขึ้นบรรทัดใหม่ในสตริงผลลัพธ์หลังจากทุก 76 ตัวอักษร base-64 หรือไม่ |

### ค่าที่คืน

สตริงที่มีการแสดงผลเป็น base-64 ของอาร์เรย์อินพุต

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) เมธอด

Base-64 เข้ารหัสช่วงขององค์ประกอบในอาร์เรย์ไบต์ที่ระบุและส่งคืนข้อมูลที่เข้ารหัสเป็นสตริง.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ของไบต์ที่มีช่วงขององค์ประกอบเพื่อเข้ารหัส |
| offset_in | int | ดัชนีขององค์ประกอบในอาร์เรย์อินพุตที่ช่วงที่จะเข้ารหัสเริ่มต้น |
| length | int | ความยาวของช่วงขององค์ประกอบที่ต้องการเข้ารหัส |
| insert_line_breaks | **bool** | ระบุว่าต้องใส่อักขระขึ้นบรรทัดใหม่ในสตริงผลลัพธ์หลังจากทุก 76 ตัวอักษร base-64 หรือไม่ |

### ค่าที่คืน

สตริงที่มีการแสดงผลเป็น base-64 ของช่วงขององค์ประกอบในอาร์เรย์อินพุต

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) เมธอด

Base-64 เข้ารหัสองค์ประกอบในอาร์เรย์ไบต์ที่ระบุและส่งคืนข้อมูลที่เข้ารหัสเป็นสตริง.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ของไบต์เพื่อเข้ารหัส |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | ระบุตัวเลือกการจัดรูปแบบของข้อมูลที่เข้ารหัส base-64 |

### ค่าที่คืน

สตริงที่มีการแสดงผลเป็น base-64 ของอาร์เรย์อินพุต

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) เมธอด

Base-64 เข้ารหัสช่วงขององค์ประกอบในอาร์เรย์ไบต์ที่ระบุและส่งคืนข้อมูลที่เข้ารหัสเป็นสตริง.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ของไบต์ที่มีช่วงขององค์ประกอบเพื่อเข้ารหัส |
| offset_in | int | ดัชนีขององค์ประกอบในอาร์เรย์อินพุตที่ช่วงที่จะเข้ารหัสเริ่มต้น |
| length | int | ความยาวของช่วงขององค์ประกอบที่ต้องการเข้ารหัส |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | ระบุตัวเลือกการจัดรูปแบบของข้อมูลที่เข้ารหัส base-64 |

### ค่าที่คืน

สตริงที่มีการแสดงผลเป็น base-64 ของช่วงขององค์ประกอบในอาร์เรย์อินพุต

## ดูเพิ่มเติม

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)