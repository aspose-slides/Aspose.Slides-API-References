---
title: Write()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เขียนอักขระที่ระบุไปยังสตรีม.
type: docs
weight: 40
url: /th/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) เมธอด

เขียนอักขระที่ระบุไปยังสตรีม.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | char_t | ค่าที่เขียน |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) เมธอด

เขียนช่วงย่อยของอักขระที่ระบุจากอาร์เรย์อักขระที่ระบุไปยังสตรีม.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | อาร์เรย์ที่มีอักขระที่จะเขียน |
| index | **int32_t** | ดัชนีเริ่มต้นจาก 0 ของ **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนอักขระในช่วงย่อยที่จะเขียน |

## StringWriter::Write(const String\&) เมธอด

เขียนสตริงที่ระบุไปยังสตรีม.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | สตริงที่จะเขียน |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)