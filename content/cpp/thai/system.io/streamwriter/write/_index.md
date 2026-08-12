---
title: Write()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เขียนอักขระที่ระบุลงในสตรีม
type: docs
weight: 79
url: /th/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) เมธอด

Writes the specified character to the stream.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char_t | อักขระที่ต้องการเขียน |

## StreamWriter::Write(const String\&) เมธอด

Writes the specified string to the stream.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | สติงที่ต้องการเขียน |

## StreamWriter::Write(const SharedPtr\<Object\>\&) เมธอด

Writes the string representation of the specified object to the stream.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | อ็อบเจ็กต์ที่ต้องการเขียน |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) เมธอด

Writes all characetrs from the specified array to the stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | อาเรย์ที่มีอักขระที่จะเขียน |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) เมธอด

Writes the specified subrange of UTF-16 characters from the specified character array to the stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | อาเรย์ที่มีอักขระที่จะเขียน |
| index | **int32_t** | ดัชนีที่เริ่มจาก 0 ของ **buffer** ที่ช่วงย่อยจะเริ่มเขียน |
| count | **int32_t** | จำนวนอักขระในช่วงย่อยที่จะเขียน; -1 หมายถึงช่วงย่อยจะสิ้นสุดเมื่ออาเรย์ **buffer** สิ้นสุด |

## StreamWriter::Write(const char_t *) เมธอด

Writes the specified c-string to the stream.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const char_t * | c-string ที่ต้องการเขียน |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) เมธอด

Writes the string representation of the specified object to the stream.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```

### Template parameters

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจ็กต์ |

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | อ็อบเจ็กต์ที่ต้องการเขียน |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [StreamWriter](../)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)