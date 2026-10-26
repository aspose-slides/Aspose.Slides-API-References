---
title: TryParse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งมีการแทนค่าเป็นสตริงของตัวเลขให้เป็นค่า double-precision floating-point ที่เทียบเท่า
type: docs
weight: 14
url: /th/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) method


แปลงสตริงที่ระบุซึ่งมีการแทนค่าเป็นสตริงของตัวเลขให้เป็นค่า double-precision floating-point ที่เทียบเท่า

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |
| result | **double**\& | ตัวแปรอ้างอิงแบบ double-precision floating-point ที่จะรับค่าผลลัพธ์ของการแปลง |

### ค่าที่ส่งกลับ

True หากการแปลงสำเร็จ, มิฉะนั้น - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) method


แปลงสตริงที่ระบุซึ่งมีการแทนค่าเป็นสตริงของตัวเลขให้เป็นค่า double-precision floating-point ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ให้มา

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมแบบบิตของค่าใน enum NumberStyles ที่ระบุรูปแบบที่อนุญาตของสตริงตัวเลข |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | พอยน์เตอร์ไปยังอ็อบเจกต์ที่มีข้อมูลการจัดรูปแบบสตริง |
| result | **double**\& | ตัวแปรอ้างอิงแบบ double-precision floating-point ที่จะรับค่าผลลัพธ์ของการแปลง |

### ค่าที่ส่งกลับ

True หากการแปลงสำเร็จ, มิฉะนั้น - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)