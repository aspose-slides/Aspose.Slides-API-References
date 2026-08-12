---
title: Parse()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นจำนวนเต็มที่มีขนาด 8-bit ที่มีเครื่องหมาย
type: docs
weight: 1
url: /th/system/sbyte/parse/
---
## SByte::Parse(const String\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นจำนวนเต็มที่มีขนาด 8 บิตที่มีเครื่องหมาย

```cpp
static int8_t System::SByte::Parse(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |

### ค่าที่ส่งกลับ

The 8-bit signed integer equal to the number represented by the specified string.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นจำนวนเต็มที่มีขนาด 8 บิตโดยใช้ข้อมูลการจัดรูปแบบที่ให้มา

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |

### ค่าที่ส่งกลับ

The 8-bit signed integer equal to the number represented by the specified string.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธodb





```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) เมธอด




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นจำนวนเต็มที่มีขนาด 8 บิตโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |

### ค่าที่ส่งกลับ

The 8-bit signed integer equal to the number represented by the specified string.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) เมธอด




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)