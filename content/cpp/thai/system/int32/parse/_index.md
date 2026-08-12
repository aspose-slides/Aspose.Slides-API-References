---
title: Parse()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มแบบ signed 32-bit ที่เทียบเท่า
type: docs
weight: 1
url: /th/system/int32/parse/
---
## Int32::Parse(const String\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มแบบมีเครื่องหมาย 32 บิตที่เทียบเท่า.

```cpp
static int32_t System::Int32::Parse(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง. |

### ค่าที่ส่งคืน

จำนวนเต็มแบบมีเครื่องหมาย 32 บิตที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ.

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มแบบมีเครื่องหมาย 32 บิตโดยใช้ข้อมูลการจัดรูปแบบที่ให้มา.

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่มีข้อมูลรูปแบบสตริง. |

### ค่าที่ส่งคืน

จำนวนเต็มแบบมีเครื่องหมาย 32 บิตที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ.

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) เมธอด

```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มแบบมีเครื่องหมาย 32 บิตโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา.

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมแบบบิตของค่าใน enum NumberStyles ที่ระบุสไตล์ที่อนุญาตของการแสดงผลตัวเลขในสตริง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่มีข้อมูลรูปแบบสตริง. |

### ค่าที่ส่งคืน

จำนวนเต็มแบบมีเครื่องหมาย 32 บิตที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ.

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) เมธอด

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) เมธอด

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) เมธอด

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) เมธอด

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int32](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [ReadOnlySpan](../../readonlyspan/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)