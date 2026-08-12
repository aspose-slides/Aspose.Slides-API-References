---
title: Parse()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ระบุของค่าที่เป็นวันที่และเวลาให้เป็นอ็อบเจ็กต์ DateTime ที่เทียบเท่า
type: docs
weight: 859
url: /th/system/datetime/parse/
---
## DateTime::Parse(const String\&) เมธอด


แปลงสตริงที่ระบุของค่าที่เป็นวันที่และเวลาให้เป็นอ็อบเจ็กต์ [DateTime](../) ที่เทียบเท่า

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | ข้อความตัวแทนของค่าที่เป็นวันที่และเวลาเพื่อทำการแปลง. |

### Return Value

อินสแตนซ์ใหม่ของคลาส [DateTime](../) ที่แสดงถึงค่าที่เป็นวันที่และเวลาเทียบเท่ากับที่แสดงโดยสตリングที่ระบุ

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) เมธอด


แปลงสตริงที่ระบุของค่าที่เป็นวันที่และเวลาให้เป็นอ็อบเจ็กต์ [DateTime](../) ที่เทียบเท่าโดยใช้ข้อมูลรูปแบบตามวัฒนธรรม

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | ข้อความตัวแทนของค่าที่เป็นวันที่และเวลาเพื่อทำการแปลง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | อ็อบเจ็กต์ [IFormatProvider](../../iformatprovider/) ที่ให้ข้อมูลรูปแบบตามวัฒนธรรม. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | การผสมแบบบิตของค่าการนับ enumeration ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับ **s**, เกี่ยวกับองค์ประกอบสไตล์ที่อาจปรากฏใน **s**, หรือเกี่ยวกับการแปลงจาก **s** ไปยังอ็อบเจ็กต์ [DateTime](../). |

### Return Value

อินสแตนซ์ใหม่ของคลาส [DateTime](../) ที่แสดงถึงค่าที่เป็นวันที่และเวลาเทียบเท่ากับที่แสดงโดยสตริงที่ระบุ

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) เมธอด




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) เมธอด




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) เมธอด




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## ดูเพิ่มเติม

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)