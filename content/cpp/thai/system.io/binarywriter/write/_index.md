---
title: Write()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เขียนค่าจำนวนเต็มบวกแบบไม่ระบุเครื่องหมาย 8-bit ที่ระบุไปยังสตรีมผลลัพธ์
type: docs
weight: 92
url: /th/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) เมธอด

เขียนค่าจำนวนเต็มบวก 8-บิตที่กำหนดไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | **uint8_t** | ค่าที่จะเขียน |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) เมธอด

เขียนช่วงย่อยของไบต์จากอาเรย์ไบต์ที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ที่บรรจุไบต์ที่จะเขียน |
| index | int | ดัชนีเริ่มต้นจาก 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | int | จำนวนองค์ประกอบในช่วงย่อยที่จะเขียน; -1 หมายถึงช่วงย่อยสิ้นสุดที่อาเรย์ **buffer** สิ้นสุด |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) เมธอด

เขียนช่วงย่อยของอักขระ UTF-16 จากอาเรย์อักขระที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | อาเรย์ที่บรรจุอักขระที่จะเขียน |
| index | int | ดัชนีเริ่มต้นจาก 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | int | จำนวนอักขระในช่วงย่อยที่จะเขียน; -1 หมายถึงช่วงย่อยสิ้นสุดที่อาเรย์ **buffer** สิ้นสุด |

## BinaryWriter::Write(bool) เมธอด

เขียนไบต์เดียวโดยมีค่า 0 หาก **value** เป็น `true` และ 1 หาก **value** เป็น `false` ไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | **bool** | ค่าตรรกะที่ระบุค่าของไบต์ที่จะเขียนไปยังสตรีมผลลัพธ์ |

## BinaryWriter::Write(char16_t) เมธอด

เขียนค่าตัวอักษรความกว้าง 16-บิตที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | char16_t | ค่าที่จะเขียน |

## BinaryWriter::Write(int16_t) เมธอด

เขียนค่าจำนวนเต็ม 16-บิตที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | **int16_t** | ค่าที่จะเขียน |

## BinaryWriter::Write(int) เมธอด

เขียนค่าจำนวนเต็ม 32-บิตที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int | ค่าที่จะเขียน |

## BinaryWriter::Write(int64_t) เมธอด

เขียนค่าจำนวนเต็ม 64-บิตที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | **int64_t** | ค่าที่จะเขียน |

## BinaryWriter::Write(uint16_t) เมธอด

เขียนค่าจำนวนเต็มบวก 16-บิตที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | **uint16_t** | ค่าที่จะเขียน |

## BinaryWriter::Write(uint32_t) เมธอด

เขียนค่าจำนวนเต็มบวก 32-บิตที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | **uint32_t** | ค่าที่จะเขียน |

## BinaryWriter::Write(uint64_t) เมธอด

เขียนค่าจำนวนเต็มบวก 64-บิตที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | **uint64_t** | ค่าที่จะเขียน |

## BinaryWriter::Write(float) เมธอด

เขียนค่าจำนวนจริงความแม่นยำเดี่ยวที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | **float** | ค่าที่จะเขียน |

## BinaryWriter::Write(double) เมธอด

เขียนค่าจำนวนจริงความแม่นยำสองเท่าที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | **double** | ค่าที่จะเขียน |

## BinaryWriter::Write(const Decimal\&) เมธอด

เขียนการแทนค่าไบต์ของค่าประเภท [Decimal](../../../system/decimal/) ที่ระบุไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | ค่าที่จะเขียน |

## BinaryWriter::Write(const String\&) เมธอด

เขียนสตริงที่มีความยาวกำหนดล่วงหน้าในรูปแบบการเข้ารหัสปัจจุบันไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | สตริงที่จะเขียน |

## BinaryWriter::Write(const char_t *) เมธอด

เขียนสตริงที่มีความยาวกำหนดล่วงหน้าในรูปแบบการเข้ารหัสปัจจุบันไปยังสตรีมผลลัพธ์

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const char_t * | สตริง C-แบบที่จะแบบเขียน |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)