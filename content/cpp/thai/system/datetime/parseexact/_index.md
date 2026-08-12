---
title: ParseExact()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงการแสดงผลสตริงที่ระบุของค่าที่เป็นวันและเวลาเป็นอ็อบเจ็กต์ DateTime ที่เทียบเท่าโดยใช้รูปแบบที่ระบุและข้อมูลรูปแบบเฉพาะวัฒนธรรม รูปแบบของการแสดงผลสตริงต้องตรงกับรูปแบบที่ระบุอย่างแม่นยำ จะขว้างข้อยกเว้นหากการแปลงล้มเหลว
type: docs
weight: 872
url: /th/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


แปลงการแสดงผลสตริงที่ระบุของค่าที่เป็นวันและเวลาเป็นอ็อบเจ็กต์ [DateTime](../) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุและข้อมูลรูปแบบเฉพาะวัฒนธรรม รูปแบบของการแสดงผลสตริงต้องตรงกับรูปแบบที่ระบุอย่างแม่นยำ จะทำการขว้างข้อยกเว้นหากการแปลงล้มเหลว

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../string/)\& | การแสดงผลสตริงของค่าที่เป็นวันและเวลาเพื่อแปลง |
| format | const [String](../../string/)\& | รูปแบบสตริง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | อ็อบเจ็กต์ [IFormatProvider](../../iformatprovider/) ที่ให้ข้อมูลรูปแบบเฉพาะวัฒนธรรม |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | การรวมแบบบิตของค่าตenumeration ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับ **s** เกี่ยวกับองค์ประกอบสไตล์ที่อาจมีอยู่ใน **s** หรือเกี่ยวกับการแปลงจาก **s** ไปยังอ็อบเจ็กต์ [DateTime](../) |

### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของคลาส [DateTime](../) ที่แสดงค่าของวันและเวลาที่เทียบเท่ากับค่าที่แสดงโดยสตริงที่ระบุ

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


แปลงการแสดงผลสตริงที่ระบุของค่าที่เป็นวันและเวลาเป็นอ็อบเจ็กต์ [DateTime](../) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุหลายรูปแบบ ข้อมูลรูปแบบเฉพาะวัฒนธรรม และสไตล์ รูปแบบของการแสดงผลสตริงต้องตรงกับหนึ่งหรือหลายรูปแบบที่ระบุอย่างแม่นยำ จะทำการขว้างข้อยกเว้นหากการแปลงล้มเหลว

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../string/)\& | การแสดงผลสตริงของค่าที่เป็นวันและเวลาเพื่อแปลง |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | อาร์เรย์ของรูปแบบสตริง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | อ็อบเจ็กต์ [IFormatProvider](../../iformatprovider/) ที่ให้ข้อมูลรูปแบบเฉพาะวัฒนธรรม |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | การรวมแบบบิตของค่าตenumeration ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับ **s** เกี่ยวกับองค์ประกอบสไตล์ที่อาจมีอยู่ใน **s** หรือเกี่ยวกับการแปลงจาก **s** ไปยังอ็อบเจ็กต์ [DateTime](../) |

### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของคลาส [DateTime](../) ที่แสดงค่าของวันและเวลาที่เทียบเท่ากับค่าที่แสดงโดยสตริงที่ระบุ

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method 




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method 




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) method 




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## ดูเพิ่มเติม

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)