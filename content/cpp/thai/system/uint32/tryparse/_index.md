---
title: TryParse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงเป็นจำนวนเต็มไม่มีเครื่องหมายขนาด 32 บิตที่เทียบเท่า
type: docs
weight: 14
url: /th/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงเป็นจำนวนเต็มไม่มีเครื่องหมายขนาด 32 บิตที่เทียบเท่า

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| result | **uint32_t**\& | อ้างอิงไปยังตัวแปรจำนวนเต็มไม่มีเครื่องหมายขนาด 32 บิตที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### Return Value

true หากการแปลงสำเร็จ, มิฉะนั้น - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงเป็นจำนวนเต็มไม่มีเครื่องหมายขนาด 32 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ให้มา

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การผสมค่าด้วยบิตของ enum NumberStyles ที่ระบุรูปแบบที่อนุญาตของการแสดงสตริงของตัวเลข |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังออบเจกต์ที่มีข้อมูลการจัดรูปแบบสตริง |
| result | **uint32_t**\& | อ้างอิงไปยังตัวแปรจำนวนเต็มไม่มีเครื่องหมายขนาด 32 บิตที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### Return Value

true หากการแปลงสำเร็จ, มิฉะนั้น - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) เมธอด




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) เมธอด




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) เมธอด




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* คลาส [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)