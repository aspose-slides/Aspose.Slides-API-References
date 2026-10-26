---
title: TryParse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งมีการแสดงผลเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มบวก 64-bit ที่เทียบเท่า.
type: docs
weight: 14
url: /th/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) เมธอด


แปลงสตริงที่ระบุซึ่งมีการแสดงผลเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มบวก 64-bit ที่เทียบเท่า

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |
| result | **uint64_t**\& | ตัวแปรอ้างอิงไปยังจำนวนเต็มบวก 64-bit ซึ่งจะเก็บผลลัพธ์ของการแปลง |

### ค่าที่ส่งกลับ

True if the conversion succeeded, otherwise - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) เมธอด


แปลงสตริงที่ระบุซึ่งมีการแสดงผลเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มบวก 64-bit ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ของตัวเลขที่กำหนดไว้

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมค่าแบบบิตของ enum NumberStyles ที่ระบุสไตล์ที่อนุญาตของการแสดงผลเป็นสตริงของตัวเลข |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่บรรจุข้อมูลการจัดรูปแบบสตริง |
| result | **uint64_t**\& | ตัวแปรอ้างอิงไปยังจำนวนเต็มบวก 64-bit ซึ่งจะเก็บผลลัพธ์ของการแปลง |

### ค่าที่ส่งกลับ

True if the conversion succeeded, otherwise - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) เมธอด




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) เมธอด




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) เมธอด




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
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