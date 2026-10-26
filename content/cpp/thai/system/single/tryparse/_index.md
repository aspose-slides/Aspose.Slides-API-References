---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นค่าเลขฐานลอยจุดความแม่นยำเดี่ยวที่เทียบเท่า
type: docs
weight: 14
url: /th/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นค่าเลขฐานลอยจุดความแม่นยำเดี่ยวที่เทียบเท่า

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| result | **float**\& | อ้างอิงไปยังตัวแปรเลขฐานลอยจุดความแม่นยำเดี่ยวที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### ค่าที่คืน

จริงหากการแปลงสำเร็จ, มิฉะนั้น - เท็จ.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) เมธอด

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นค่าเลขฐานลอยจุดความแม่นยำเดี่ยวโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ให้มา

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมแบบบิตของค่าใน enum NumberStyles ที่ระบุรูปแบบที่อนุญาตของการแสดงผลของตัวเลขในสตริง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจกต์ที่มีข้อมูลรูปแบบสตริง |
| result | **float**\& | อ้างอิงไปยังตัวแปรเลขฐานลอยจุดความแม่นยำเดี่ยวที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### ค่าที่คืน

จริงหากการแปลงสำเร็จ, มิฉะนั้น - เท็จ.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) เมธอด

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) เมธอด

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) เมธอด

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
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