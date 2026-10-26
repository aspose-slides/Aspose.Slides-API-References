---
title: WriteLine()
second_title: อ้างอิง API ของ Aspose.Slides for C++
description: เขียนอักขระจบบรรทัดไปยังสตรีม.
type: docs
weight: 92
url: /th/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() เมธอด

เขียนอักขระจบบรรทัดไปยังสตรีม.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) เมธอด

เขียนสตริงที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | สตริงที่จะเขียน |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) เมธอด

เขียนการแสดงผลเป็นสตริงของอ็อบเจกต์ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | อ็อบเจกต์ที่จะเขียน |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) เมธอด

เขียนอักขระทั้งหมดจากอาร์เรย์ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | อาร์เรย์ที่บรรจุอักขระที่จะเขียน |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) เมธอด

เขียนช่วงย่อยของอักขระ UTF-16 จากอาร์เรย์อักขระที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | อาร์เรย์ที่บรรจุอักขระที่จะเขียน |
| index | **int32_t** | ดัชนีเริ่มต้นที่ 0 ของ **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนอักขระในช่วงย่อยที่จะเขียน; -1 ระบุว่าช่วงย่อยสิ้นสุดที่จบของอาร์เรย์ **buffer** |

## StreamWriter::WriteLine(const char_t *) เมธอด

เขียนสตริง C ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const char_t * | สตริง C ที่จะเขียน |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) เมธอด

เขียนการแสดงผลเป็นสตริงของอ็อบเจกต์ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจกต์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | อ็อบเจกต์ที่จะเขียน |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)