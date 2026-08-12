---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงการแสดงผลสตริงที่ระบุของค่าที่เป็นวันที่และเวลาให้เป็นอ็อบเจ็กต์ DateTime ที่เทียบเท่า
type: docs
weight: 885
url: /th/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) method


แปลงการแสดงผลสตริงที่ระบุของค่าที่เป็นวันที่และเวลาให้เป็นอ็อบเจ็กต์ [DateTime](../) ที่เทียบเท่า

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../string/)\& | การแสดงผลสตริงของค่าที่เป็นวันที่และเวลาเพื่อแปลง |
| result | [DateTime](../)\& | อาร์กิวเมนต์ผลลัพธ์ที่หากการแปลงสำเร็จ จะบรรจุผลลัพธ์ของการแปลง |

### ค่าที่ส่งกลับ

จริงหากการแปลงสำเร็จ, มิฉะนั้น - เท็จ.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


แปลงการแสดงผลสตริงที่ระบุของค่าที่เป็นวันที่และเวลาให้เป็นอ็อบเจ็กต์ [DateTime](../) ที่เทียบเท่าโดยใช้ข้อมูลรูปแบบเฉพาะวัฒนธรรมและสไตล์ที่ระบุ

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../string/)\& | การแสดงผลสตริงของค่าที่เป็นวันที่และเวลาเพื่อแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | วัตถุ [IFormatProvider](../../iformatprovider/) ที่ให้ข้อมูลรูปแบบเฉพาะวัฒนธรรม |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | การผสมแบบบิตของค่า enumeration ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับ **s**, เกี่ยวกับองค์ประกอบสไตล์ที่อาจมีอยู่ใน **s**, หรือเกี่ยวกับการแปลงจาก **s** ไปยังอ็อบเจ็กต์ [DateTime](../) |
| result | [DateTime](../)\& | อาร์กิวเมนต์ผลลัพธ์ที่หากการแปลงสำเร็จ จะบรรจุผลลัพธ์ของการแปลง |

### ค่าที่ส่งกลับ

จริงหากการแปลงสำเร็จ, มิฉะนั้น - เท็จ.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## ดูเพิ่มเติม

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)