---
title: Parse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าตัวเลขเป็นสตริงให้เป็นค่าจำนวนจุดลอยแบบ single-precision ที่เท่ากับตัวเลขนั้น
type: docs
weight: 1
url: /th/system/single/parse/
---
## Single::Parse(const String\&) เมธอด

แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าตัวเลขเป็นสตริงให้เป็นค่าจำนวนจุดลอยแบบ single-precision ที่เท่ากับตัวเลขนั้น

```cpp
static float System::Single::Parse(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |

### ค่าที่คืน

ค่าจำนวนจุดลอยแบบ single-precision ที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าตัวเลขเป็นสตริงให้เป็นค่าจำนวนจุดลอยแบบ single-precision ที่เท่ากับตัวเลขนั้นโดยใช้ข้อมูลการจัดรูปแบบที่ให้มา

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจกต์ที่มีข้อมูลการจัดรูปแบบสตริง |

### ค่าที่คืน

ค่าจำนวนจุดลอยแบบ single-precision ที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) เมธอด




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าตัวเลขเป็นสตริงให้เป็นค่าจำนวนจุดลอยแบบ single-precision ที่เท่ากับตัวเลขนั้นโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ของตัวเลขที่ให้มา

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมแบบบิตของค่าตัวเลขในอีนนัม NumberStyles ที่ระบุสไตล์ที่อนุญาตสำหรับการแทนค่าตัวเลข |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจกต์ที่มีข้อมูลการจัดรูปแบบสตริง |

### ค่าที่คืน

ค่าจำนวนจุดลอยแบบ single-precision ที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) เมธอด




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)