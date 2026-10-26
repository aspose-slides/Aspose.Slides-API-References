---
title: Parse()
second_title: Aspose.Slides for C++ เอกสารอ้างอิง API
description: แปลงสตริงเป็นอ็อบเจ็กต์ TimeSpan ที่เทียบเท่า.
type: docs
weight: 534
url: /th/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) เมธอด

แปลงสตริงเป็นอ็อบเจ็กต์ [TimeSpan](../) ที่เทียบเท่า.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | สตริงอินพุต. |

### ค่าที่คืนค่า

ช่วงเวลาที่สอดคล้องกับสตริง.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงสตริงเป็นอ็อบเจ็กต์ [TimeSpan](../) ที่เทียบเท่าโดยใช้ผู้ให้รูปแบบที่ระบุ.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | สตริงอินพุต. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้รูปแบบที่จัดหาข้อมูลการฟอร์แมตตามวัฒนธรรม. |

### ค่าที่คืนค่า

ช่วงเวลาที่สอดคล้องกับสตริง.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) เมธอด




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) เมธอด




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [TimeSpan](../)
* คลาส [String](../../string/)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* คลาส [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)