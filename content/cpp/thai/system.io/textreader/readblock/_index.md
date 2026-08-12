---
title: ReadBlock()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านจำนวนอักขระสูงสุดที่ระบุจากตัวอ่านข้อความปัจจุบันและเขียนข้อมูลลงในบัฟเฟอร์ เริ่มจากตำแหน่งดัชนีที่ระบุ.
type: docs
weight: 53
url: /th/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) เมธอด


อ่านจำนวนอักขระสูงสุดที่ระบุจากตัวอ่านข้อความปัจจุบันและเขียนข้อมูลลงในบัฟเฟอร์ เริ่มต้นที่ตำแหน่งดัชนีที่ระบุ

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระสำหรับเขียนข้อมูลที่อ่านได้ |
| index | int | ดัชนีเริ่มต้นจาก 0 ใน **buffer** เพื่อเริ่มเขียน |
| count | int | จำนวนอักขระสูงสุดที่จะอ่าน |

### ค่าที่ส่งกลับ

จำนวนอักขระที่อ่านได้จริง

## ดูเพิ่มเติม

* ชนิดกำหนดค่า [ArrayPtr](../../../system/arrayptr/)
* คลาส [TextReader](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)