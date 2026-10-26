---
title: TryParseExact()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แปลงสตริงเป็นอ็อบเจกต์ TimeSpan ที่เทียบเท่าโดยใช้รูปแบบที่ระบุและผู้จัดหาแบบฟอร์ม แล้วส่งคืนผลลัพธ์ของการแปลง
type: docs
weight: 573
url: /th/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


แปลงสตริงเป็นอ็อบเจกต์ [TimeSpan](../) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุและผู้จัดหาแบบฟอร์ม และส่งคืนผลลัพธ์ของการแปลง

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | สตริงอินพุต. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) ของสตริงรูปแบบ. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้จัดหาแบบฟอร์มที่ให้ข้อมูลการจัดรูปแบบตามวัฒนธรรม |
| result | [TimeSpan](../)\& | ช่วงเวลาที่สอดคล้องกับสตริง. |

### ค่าที่คืน

True หากสตริงถูกแปลงสำเร็จ; มิฉะนั้น false.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method


แปลงสตริงเป็นอ็อบเจกต์ [TimeSpan](../) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุ ผู้จัดหาแบบฟอร์ม และสไตล์ และส่งคืนผลลัพธ์ของการแปลง

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | สตริงอินพุต. |
| format | const [String](../../string/)\& | สตริงรูปแบบมาตรฐานหรือกำหนดเอง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้จัดหาแบบฟอร์มที่ให้ข้อมูลการจัดรูปแบบตามวัฒนธรรม |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | กำหนดองค์ประกอบที่อาจปรากฏในสตริงอินพุต. |
| result | [TimeSpan](../)\& | ช่วงเวลาที่สอดคล้องกับสตริง. |

### ค่าที่คืน

True หากสตริงถูกแปลงสำเร็จ; มิฉะนั้น false.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method


แปลงสตริงเป็นอ็อบเจกต์ [TimeSpan](../) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุ ผู้จัดหาแบบฟอร์ม และสไตล์ และส่งคืนผลลัพธ์ของการแปลง

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | สตริงอินพุต. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) ของสตริงรูปแบบ. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้จัดหาแบบฟอร์มที่ให้ข้อมูลการจัดรูปแบบตามวัฒนธรรม |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | กำหนดองค์ประกอบที่อาจปรากฏในสตริงอินพุต. |
| result | [TimeSpan](../)\& | ช่วงเวลา ที่สอดคล้องกับสตริง. |

### ค่าที่คืน

True หากสตริงถูกแปลงสำเร็จ; มิฉะนั้น false.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


แปลงสตริงเป็นอ็อบเจกต์ [TimeSpan](../) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุและผู้จัดหาแบบฟอร์ม และส่งคืนผลลัพธ์ของการแปลง

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | สตริงอินพุต. |
| format | const [String](../../string/)\& | สตริงรูปแบบมาตรฐานหรือกำหนดเอง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้จัดหาแบบฟอร์มที่ให้ข้อมูลการจัดรูปแบบตามวัฒนธรรม |
| result | [TimeSpan](../)\& | ช่วงเวลา ที่สอดคล้องกับสตริง. |

### ค่าที่คืน

True หากสตริงถูกแปลงสำเร็จ; มิฉะนั้น false.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## ดูเพิ่มเติม

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [TimeSpan](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)