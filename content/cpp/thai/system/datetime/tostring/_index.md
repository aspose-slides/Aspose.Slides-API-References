---
title: ToString()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนสตริงที่เป็นการแสดงค่าของวันที่และเวลาที่เป็นตัวแทนของวัตถุปัจจุบันโดยใช้รูปแบบการจัดรูปแบบที่กำหนดโดยวัฒนธรรมปัจจุบัน
type: docs
weight: 482
url: /th/system/datetime/tostring/
---
## DateTime::ToString() const เมธอด

ส่งคืนสตริงที่เป็นการแสดงค่าของวันที่และเวลาที่เป็นตัวแทนของวัตถุปัจจุบันโดยใช้รูปแบบการจัดรูปแบบที่กำหนดโดยวัฒนธรรมปัจจุบัน

```cpp
String System::DateTime::ToString() const
```

### ค่าที่ส่งกลับ

สตริงที่เป็นการแสดงค่าที่เป็นตัวแทนของวัตถุปัจจุบัน

## DateTime::ToString(const String\&) const เมธอด

ส่งคืนสตริงที่เป็นการแสดงค่าของวันที่และเวลาที่เป็นตัวแทนของวัตถุปัจจุบันโดยใช้รูปแบบที่ระบุและรูปแบบการจัดรูปแบบที่กำหนดโดยวัฒนธรรมปัจจุบัน

```cpp
String System::DateTime::ToString(const String &format) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | const [String](../../string/)\& | สตริงรูปแบบ |

### ค่าที่ส่งกลับ

สตริงที่เป็นการแสดงค่าที่เป็นตัวแทนของวัตถุปัจจุบันโดยจัดรูปแบบตามรูปแบบที่กำหนดโดย **format** และวัฒนธรรมปัจจุบัน

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const เมธอด

ส่งคืนสตริงที่เป็นการแสดงค่าของวันที่และเวลาที่เป็นตัวแทนของวัตถุปัจจุบันโดยใช้ข้อมูลรูปแบบที่ระบุ

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ออบเจ็กต์ที่เป็นตัวแทนของข้อมูลรูปแบบ |

### ค่าที่ส่งกลับ

สตริงที่เป็นการแสดงค่าที่เป็นตัวแทนของวัตถุปัจจุบันโดยจัดรูปแบบตามข้อมูลรูปแบบที่จัดหาโดย **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const เมธอด




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const เมธอด




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const เมธอด




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const เมธอด

ส่งคืนสตริงที่เป็นการแสดงค่าของวันที่และเวลาที่เป็นตัวแทนของวัตถุปัจจุบันโดยใช้ข้อมูลรูปแบบที่ระบุ

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | const [String](../../string/)\& | สตริงรูปแบบ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ออบเจ็กต์ที่เป็นตัวแทนของข้อมูลรูปแบบ |

### ค่าที่ส่งกลับ

สตริงที่เป็นการแสดงค่าที่เป็นตัวแทนของวัตถุปัจจุบันโดยจัดรูปแบบตามข้อมูลรูปแบบที่จัดหาโดย **provider** และสตริงรูปแบบ **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const เมธอด




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const เมธอด




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const เมธอด




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [DateTime](../)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* คลาส [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)