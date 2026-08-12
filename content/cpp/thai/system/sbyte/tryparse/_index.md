---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มมีเครื่องหมาย 8-bit ที่เทียบเท่า
type: docs
weight: 14
url: /th/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มมีเครื่องหมาย 8-bit ที่เทียบเท่า

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| result | **int8_t**\& | ตัวอ้างอิงไปยังตัวแปรจำนวนเต็มมีเครื่องหมาย 8-bit ที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### ค่าที่คืน

True หากการแปลงสำเร็จ, มิฉะนั้น - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มมีเครื่องหมาย 8-bit โดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมแบบบิตของค่าตัวแปร NumberStyles enum ที่ระบุสไตล์ที่อนุญาตของการแสดงผลตัวเลขในสตริง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่บรรจุข้อมูลการจัดรูปแบบสตริง |
| result | **int8_t**\& | ตัวอ้างอิงไปยังตัวแปรจำนวนเต็มมีเครื่องหมาย 8-bit ที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### ค่าที่คืน

True หากการแปลงสำเร็จ, มิฉะนั้น - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) เมธอด




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) เมธอด




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) เมธอด




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
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