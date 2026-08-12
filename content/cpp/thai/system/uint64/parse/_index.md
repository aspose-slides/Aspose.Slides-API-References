---
title: Parse()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นจำนวนเต็มบวกขนาด 64 บิตที่เท่ากัน
type: docs
weight: 1
url: /th/system/uint64/parse/
---
## UInt64::Parse(const String\&) method

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นจำนวนเต็มบวกขนาด 64 บิตที่เท่ากัน

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |

### ค่าที่ส่งกลับ

จำนวนเต็มบวกขนาด 64 บิตที่เท่ากับจำนวนที่แสดงโดยสตริงที่ระบุ

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นจำนวนเต็มบวกขนาด 64 บิตที่เท่ากันโดยใช้ข้อมูลการจัดรูปแบบที่ให้มา

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่มีข้อมูลการจัดรูปแบบสตริง |

### ค่าที่ส่งกลับ

จำนวนเต็มบวกขนาด 64 บิตที่เท่ากับจำนวนที่แสดงโดยสตริงที่ระบุ

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) method




```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นจำนวนเต็มบวกขนาด 64 บิตที่เท่ากันโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ให้มา

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมค่าตามบิตของค่า enum NumberStyles ที่ระบุรูปแบบที่อนุญาตของการแสดงผลสตริงของจำนวน |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่มีข้อมูลการจัดรูปแบบสตริง |

### ค่าที่ส่งกลับ

จำนวนเต็มบวกขนาด 64 บิตที่เท่ากับจำนวนที่แสดงโดยสตริงที่ระบุ

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)