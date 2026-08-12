---
title: ToString()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนการแสดงผลเป็นสตริงของค่าที่วัตถุเป็นตัวแทน
type: docs
weight: 352
url: /th/system/decimal/tostring/
---
## Decimal::ToString() const เมธอด

ส่งคืนการแสดงผลเป็นสตริงของค่าที่วัตถุเป็นตัวแทน

```cpp
String System::Decimal::ToString() const
```
## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const เมธอด

แปลงอ็อบเจ็กต์ปัจจุบันเป็นสตริงโดยใช้ข้อมูลรูปแบบที่เฉพาะเจาะจงตามวัฒนธรรม

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | อ็อบเจ็กต์ [IFormatProvider](../../iformatprovider/) ที่ให้ข้อมูลรูปแบบที่เฉพาะเจาะจงตามวัฒนธรรม |

### ค่าที่ส่งคืน

การแสดงผลเป็นสตริงของอ็อบเจ็กต์ปัจจุบัน

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const เมธอด




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const เมธอด




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const เมธอด




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const เมธอด

แปลงอ็อบเจ็กต์ปัจจุบันเป็นการแสดงผลเป็นสตริงโดยใช้รูปแบบสตริงที่กำหนดและข้อมูลรูปแบบที่เฉพาะเจาะจงตามวัฒนธรรมที่จัดหาโดยอ็อบเจ็กต์ [IFormatProvider](../../iformatprovider/) ที่ระบุ

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | const [String](../../string/)\& | รูปแบบสตริง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | อ็อบเจ็กต์ [IFormatProvider](../../iformatprovider/) ที่ให้ข้อมูลรูปแบบที่เฉพาะเจาะจงตามวัฒนธรรม |

### ค่าที่ส่งคืน

การแสดงผลเป็นสตริงของอ็อบเจ็กต์ปัจจุบัน

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const เมธอด




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const เมธอด




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const เมธอด




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [Decimal](../)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* คลาส [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)