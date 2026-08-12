---
title: Read()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านอักขระเดียวจากสตรีม.
type: docs
weight: 40
url: /th/system.io/textreader/read/
---
## TextReader::Read() เมธอด

อ่านอักขระเดียวจากสตรีม.

```cpp
virtual int System::IO::TextReader::Read()
```

### Return Value

อ่านอักขระที่เข้ารหัสด้วย UTF-16; หากอักขระที่อ่านได้แสดงด้วยสองโค้ดพอยท์ในการเข้ารหัส UTF-16 จะคืนเฉพาะ high surrogate เท่านั้น.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) เมธอด

อ่านจำนวนอักขระที่ระบุจากสตรีมและเขียนลงในอาร์เรย์อักขระที่ระบุโดยเริ่มที่ตำแหน่งที่ระบุ.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Arguments

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อาร์เรย์อักขระ UTF-16 ที่ใช้เขียนอักขระที่อ่านจากสตรีมลงไป |
| index | int | ดัชนีฐานศูนย์ใน **buffer** ที่จะเริ่มเขียน |
| count | int | จำนวนอักขระที่ต้องการอ่านจากสตรีม |

### Return Value

จำนวนอักขระที่อ่านจากสตรีม

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [TextReader](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)