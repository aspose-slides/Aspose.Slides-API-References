---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงเป็นจำนวนเต็มแบบมีเครื่องหมายขนาด 16 บิตที่เทียบเท่า
type: docs
weight: 14
url: /th/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแทนค่าของจำนวนเป็นสตริงเป็นจำนวนเต็มแบบมีเครื่องหมายขนาด 16 บิตที่เทียบเท่า

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง. |
| result | **int16_t**\& | การอ้างอิงไปยังตัวแปรจำนวนเต็มแบบมีเครื่องหมายขนาด 16 บิตที่ผลลัพธ์ของการแปลงถูกเก็บไว้. |

### ค่าที่ส่งคืน

True หากการแปลงสำเร็จ, มิฉะนั้น - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแทนค่าของจำนวนเป็นสตริงเป็นจำนวนเต็มแบบมีเครื่องหมายขนาด 16 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ระบุ

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การผสมแบบบิตของค่าจาก enum NumberStyles ที่กำหนดรูปแบบที่อนุญาตของการแทนค่าจำนวนในสตริง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจกต์ที่บรรจุข้อมูลรูปแบบสตริง. |
| result | **int16_t**\& | การอ้างอิงไปยังตัวแปรจำนวนเต็มแบบมีเครื่องหมายขนาด 16 บิตที่ผลลัพธ์ของการแปลงถูกเก็บไว้. |

### ค่าที่ส่งคืน

True หากการแปลงสำเร็จ, มิฉะนั้น - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) เมธอด

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) เมธอด

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) เมธอด

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
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