---
title: Read()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านอักขระตัวเดียวจากสตรีม.
type: docs
weight: 40
url: /th/system.io/streamreader/read/
---
## StreamReader::Read() เมธอด

อ่านอักขระตัวเดียวจากสตรีม

```cpp
virtual int System::IO::StreamReader::Read() override
```

### ค่าที่คืน

อักขระที่อ่านได้โดยเข้ารหัสด้วย UTF-16; หากอักขระที่อ่านถูกแทนด้วยสองโค้ดพอยต์ในรูปแบบ UTF-16 จะคืนค่าเฉพาะส่วน high surrogate เท่านั้น

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) เมธอด

อ่านจำนวนอักขระที่ระบุจากสตรีม, แปลงเป็นการเข้ารหัส UTF-16 และเขียนอักขระ UTF-16 ที่ได้ลงในอาร์เรย์อักขระที่ระบุโดยเริ่มจากตำแหน่งที่กำหนด

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อาเรย์อักขระ UTF-16 ที่จะเขียนอักขระที่อ่านจากสตรีมลงไป |
| index | int | ดัชนีเริ่มต้นที่ 0 ใน **buffer** ที่จะเริ่มเขียน |
| count | int | จำนวนอักขระที่จะอ่านจากสตรีม |

### ค่าที่คืน

จำนวนอักขระที่อ่านจากสตรีม

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)