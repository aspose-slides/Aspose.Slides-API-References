---
title: Parse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งประกอบด้วยการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มมีเครื่องหมาย 64 บิตที่เทียบเท่า
type: docs
weight: 1
url: /th/system/int64/parse/
---
## Int64::Parse(const String\&) เมธอด

แปลงสตริงที่ระบุซึ่งประกอบด้วยการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มมีเครื่องหมาย 64 บิตที่เทียบเท่า

```cpp
static int64_t System::Int64::Parse(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |

### ค่าที่ส่งคืน

จำนวนเต็มมีเครื่องหมาย 64 บิตที่เทียบเท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งประกอบด้วยการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มมีเครื่องหมาย 64 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ให้ไว้

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังออบเจกต์ที่มีข้อมูลการจัดรูปแบบสตริง |

### ค่าที่ส่งคืน

จำนวนเต็มมีเครื่องหมาย 64 บิตที่เทียบเท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) เมธอด




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งประกอบด้วยการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มมีเครื่องหมาย 64 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ให้ไว้

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมแบบบิตของค่าตัวแปร enum NumberStyles ที่ระบุรูปแบบที่อนุญาตสำหรับการแสดงผลสตริงของจำนวน |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังออบเจกต์ที่มีข้อมูลการจัดรูปแบบสตริง |

### ค่าที่ส่งคืน

จำนวนเต็มมีเครื่องหมาย 64 บิตที่เทียบเท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) เมธอด




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)