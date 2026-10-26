---
title: Parse()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มแบบมีเครื่องหมาย 16-bit ที่เทียบเท่า
type: docs
weight: 1
url: /th/system/int16/parse/
---
## Int16::Parse(const String\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มแบบมีเครื่องหมาย 16-bit ที่เทียบเท่า

```cpp
static int16_t System::Int16::Parse(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง. |

### ค่าที่คืนกลับ

จำนวนเต็มแบบมีเครื่องหมาย 16-bit ที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มแบบมีเครื่องหมาย 16-bit โดยใช้ข้อมูลการจัดรูปแบบที่ให้มา

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | พอยน์เตอร์ไปยังออบเจกต์ที่มีข้อมูลรูปแบบสตริง. |

### ค่าที่คืนกลับ

จำนวนเต็มแบบมีเครื่องหมาย 16-bit ที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) เมธอด

```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มแบบมีเครื่องหมาย 16-bit โดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การผสมแบบบิตของค่าใน enum NumberStyles ที่ระบุสไตล์ที่อนุญาตของการแสดงผลสตริงของตัวเลข. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | พอยน์เตอร์ไปยังออบเจกต์ที่มีข้อมูลรูปแบบสตริง. |

### ค่าที่คืนกลับ

จำนวนเต็มแบบมีเครื่องหมาย 16-bit ที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) เมธอด

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int16](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)