---
title: TryParseExact()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงการแสดงผลแบบสตริงที่ระบุของค่า วันที่และเวลา ให้เป็นอ็อบเจ็กต์ DateTime ที่เทียบเท่าโดยใช้รูปแบบที่ระบุ ข้อมูลรูปแบบเฉพาะวัฒนธรรม และสไตล์ รูปแบบของการแสดงผลแบบสตริงต้องตรงกับรูปแบบที่ระบุอย่างแม่นยำ
type: docs
weight: 898
url: /th/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


แปลงการแสดงผลแบบสตริงที่ระบุของค่า วันที่และเวลา ให้เป็นอ็อบเจ็กต์ [DateTime](../) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุ ข้อมูลรูปแบบเฉพาะวัฒนธรรม และสไตล์ รูปแบบของการแสดงผลแบบสตริงต้องตรงกับรูปแบบที่ระบุอย่างแม่นยำ

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| s | const [String](../../string/)\& | การแสดงผลแบบสตริงของค่า วันที่และเวลา ที่ต้องการแปลง |
| format | const [String](../../string/)\& | รูปแบบสตริง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | อ็อบเจ็กต์ [IFormatProvider](../../iformatprovider/) ที่ให้ข้อมูลรูปแบบเฉพาะวัฒนธรรม |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | การผสมแบบบิตของค่าการนับที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับ **s** เกี่ยวกับองค์ประกอบสไตล์ที่อาจปรากฏใน **s** หรือเกี่ยวกับการแปลงจาก **s** เป็นอ็อบเจ็กต์ [DateTime](../) |
| result | [DateTime](../)\& | อาร์กิวเมนต์ผลลัพธ์ที่หากการแปลงสำเร็จ จะมีค่าผลลัพธ์ของการแปลง |

### ค่าที่คืนกลับ

True if conversion succeeds, otherwise - false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


แปลงการแสดงผลแบบสตริงที่ระบุของค่า วันที่และเวลา ให้เป็นอ็อบเจ็กต์ [DateTime](../) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุหลายรูปแบบ ข้อมูลรูปแบบเฉพาะวัฒนธรรม และสไตล์ รูปแบบของการแสดงผลแบบสตริงต้องตรงกับรูปแบบที่ระบุอย่างน้อยหนึ่งรูปแบบอย่างแม่นยำ

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| s | const [String](../../string/)\& | การแสดงผลแบบสตริงของค่า วันที่และเวลา ที่ต้องการแปลง |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | อาเรย์ของรูปแบบสตริง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | อ็อบเจ็กต์ [IFormatProvider](../../iformatprovider/) ที่ให้ข้อมูลรูปแบบเฉพาะวัฒนธรรม |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | การผสมแบบบิตของค่าการนับที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับ **s** เกี่ยวกับองค์ประกอบสไตล์ที่อาจปรากฏใน **s** หรือเกี่ยวกับการแปลงจาก **s** เป็นอ็อบเจ็กต์ [DateTime](../) |
| result | [DateTime](../)\& | อาร์กิวเมนต์ผลลัพธ์ที่หากการแปลงสำเร็จ จะมีค่าผลลัพธ์ของการแปลง |

### ค่าที่คืนกลับ

True if conversion succeeds, otherwise - false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## ดูเพิ่มเติม

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)