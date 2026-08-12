---
title: TryParse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงเป็นอ็อบเจกต์ TimeSpan ที่เทียบเท่าและส่งคืนผลลัพธ์ของการแปลง
type: docs
weight: 560
url: /th/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) method

แปลงสตริงเป็นอ็อบเจกต์ [TimeSpan](../) เทียบเท่าและส่งคืนผลลัพธ์ของการแปลง

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | สตริงอินพุต |
| result | [TimeSpan](../)\& | ช่วงเวลาที่สอดคล้องกับสตริง |

### Return Value

True if string was converted successfully; otherwise, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method

แปลงสตริงเป็นอ็อบเจกต์ [TimeSpan](../) เทียบเท่าโดยใช้ผู้จัดหาฟอร์แมตที่ระบุและส่งคืนผลลัพธ์ของการแปลง

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | สตริงอินพุต |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้จัดหาฟอร์แมตที่ให้ข้อมูลการจัดรูปแบบตามวัฒนธรรมเฉพาะ |
| result | [TimeSpan](../)\& | ช่วงเวลาที่สอดคล้องกับสตริง |

### Return Value

True if string was converted successfully; otherwise, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [TimeSpan](../)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* คลาส [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)