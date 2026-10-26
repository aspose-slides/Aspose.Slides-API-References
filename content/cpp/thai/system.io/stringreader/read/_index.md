---
title: Read()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: อ่านอักขระเดียวจากสตรีม.
type: docs
weight: 40
url: /th/system.io/stringreader/read/
---
## StringReader::Read() เมธอด


อ่านอักขระเดียวจากสตรีม.

```cpp
virtual int System::IO::StringReader::Read() override
```


### ค่าที่ส่งกลับ

อักขระที่อ่านได้ หรือ -1 หากไม่มีอักขระใดถูกอ่าน

## StringReader::Read(ArrayPtr\<char_t\>, int, int) เมธอด


อ่านจำนวนอักขระที่ระบุจากสตรีมไปยังอาร์เรย์อักขระที่ระบุโดยเริ่มจากตำแหน่งที่ระบุ.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อาร์เรย์อักขระที่ใช้เขียนอักขระที่อ่านจากสตรีม |
| index | int | ดัชนีเริ่มจากศูนย์ใน **buffer** ที่จะเริ่มเขียน |
| count | int | จำนวนอักขระที่จะอ่านจากสตรีม |

### ค่าที่ส่งกลับ

จำนวนอักขระที่อ่านจากสตรีม

## ดูเพิ่ม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)