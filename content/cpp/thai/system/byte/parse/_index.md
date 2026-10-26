---
title: Parse()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นตัวเลขให้เป็นจำนวนเต็มไม่เป็นลบขนาด 8 บิตที่เทียบเท่า
type: docs
weight: 1
url: /th/system/byte/parse/
---
## Byte::Parse(const String\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นตัวเลขให้เป็นจำนวนเต็มไม่เป็นลบขนาด 8 บิตที่เทียบเท่า

```cpp
static uint8_t System::Byte::Parse(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |

### ค่าที่คืนค่า

จำนวนเต็มไม่เป็นลบขนาด 8 บิตที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นตัวเลขให้เป็นจำนวนเต็มไม่เป็นลบขนาด 8 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ให้มา

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่มีข้อมูลรูปแบบสตริง |

### ค่าที่คืนค่า

จำนวนเต็มไม่เป็นลบขนาด 8 บิตที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) เมธอด




```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นตัวเลขให้เป็นจำนวนเต็มไม่เป็นลบขนาด 8 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ของตัวเลขที่ให้มา

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การผสมแบบบิตวายของค่าจาก enum NumberStyles ที่ระบุรูปแบบที่อนุญาตของการแสดงผลสตริงของจำนวน |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่มีข้อมูลรูปแบบสตริง |

### ค่าที่คืนค่า

จำนวนเต็มไม่เป็นลบขนาด 8 บิตที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) เมธอด 




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)