---
title: Parse()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า
type: docs
weight: 1
url: /th/system/uint16/parse/
---
## UInt16::Parse(const String\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มบวกขนาด 16 บิตที่เท่ากับ

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```

### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะแปลง. |

### ค่าที่ส่งคืน

จำนวนเต็มบวกขนาด 16 บิตที่เท่ากับตัวเลขที่สตริงที่ระบุแทนค่า

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มบวกขนาด 16 บิตที่เท่ากับโดยใช้ข้อมูลการจัดรูปแบบที่ให้มา

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะแปลง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่มีข้อมูลการจัดรูปแบบสตริง. |

### ค่าที่ส่งคืน

จำนวนเต็มบวกขนาด 16 บิตที่เท่ากับตัวเลขที่สตริงที่ระบุแทนค่า

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) เมธอด




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มบวกขนาด 16 บิตที่เท่ากับโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะแปลง. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมแบบบิตของค่าจาก enum NumberStyles ที่ระบุรูปแบบที่อนุญาตของการแทนค่าตัวเลขเป็นสตริง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่มีข้อมูลการจัดรูปแบบสตริง. |

### ค่าที่ส่งคืน

จำนวนเต็มบวกขนาด 16 บิตที่เท่ากับตัวเลขที่สตริงที่ระบุแทนค่า

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) เมธอด




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)