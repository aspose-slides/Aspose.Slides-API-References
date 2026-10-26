---
title: Read()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: อ่านอักขระเดี่ยวหนึ่งตัวจากสตรีมอินพุต.
type: docs
weight: 66
url: /th/system.io/binaryreader/read/
---
## BinaryReader::Read() เมธอด


อ่านอักขระเดี่ยวหนึ่งตัวจากสตรีมอินพุต.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### ค่าที่ส่งคืน

อักขระที่อ่านจะถูกเข้ารหัสด้วย UTF-16; หากอักขระที่อ่านแสดงด้วยสองโค้ดพอยต์ใน UTF-16 จะส่งกลับเฉพาะส่วนสูงของ surrogate เท่านั้น.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) เมธอด


อ่านจำนวนไบต์ที่ระบุจากสตรีมอินพุตและเขียนลงในอาเรย์ไบต์ที่ระบุ.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ใช้เขียนไบต์ที่อ่าน |
| index | int | ตำแหน่งเริ่มต้นที่นับจากศูนย์ใน **buffer** เพื่อเริ่มเขียน |
| count | int | จำนวนไบต์ที่ต้องการอ่าน |

### ค่าที่ส่งคืน

จำนวนไบต์ที่อ่านได้

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) เมธอด


อ่านจำนวนอักขระที่ระบุจากสตรีมอินพุต, แปลงเป็นการเข้ารหัส UTF-16 และเขียนอักขระ UTF-16 ที่ได้ลงในอาเรย์อักขระที่ระบุโดยเริ่มจากตำแหน่งที่ระบุ.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อาเรย์อักขระ UTF-16 ที่ใช้เขียนอักขระที่อ่านจากสตรีมอินพุต |
| index | int | ดัชนีเริ่มต้นที่นับจากศูนย์ใน **buffer** เพื่อเริ่มเขียน |
| count | int | จำนวนอักขระที่ต้องการอ่านจากสตรีม |

### ค่าที่ส่งคืน

จำนวนอักขระที่อ่านจากสตรีมอินพุต

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [BinaryReader](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)