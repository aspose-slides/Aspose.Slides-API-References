---
title: Concat()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รวมอาร์เรย์ของสตริง.
type: docs
weight: 1
url: /th/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) function

รวมอาร์เรย์ของสตริง

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) ของสตริงเพื่อเชื่อมต่อ |

### ค่าที่คืน

สตริงที่รวม

## System::StringExtra::Concat(const String\&, const String\&) function

รวมสตริง

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | สตริงแรกเพื่อรวม |
| str1 | const [String](../../system/string/)\& | สตริงที่สองเพื่อรวม |

### ค่าที่คืน

สตริงพารามิเตอร์ที่รวม

## System::StringExtra::Concat(const String\&, const String\&, const String\&) function

รวมสตริง

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | สตริงแรกเพื่อรวม |
| str1 | const [String](../../system/string/)\& | สตริงที่สองเพื่อรวม |
| str2 | const [String](../../system/string/)\& | สตริงที่สามเพื่อรวม |

### ค่าที่คืน

สตริงพารามิเตอร์ที่รวม

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) function

รวมสตริง

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | สตริงแรกเพื่อรวม |
| str1 | const [String](../../system/string/)\& | สตริงที่สองเพื่อรวม |
| str2 | const [String](../../system/string/)\& | สตริงที่สามเพื่อรวม |
| str3 | const [String](../../system/string/)\& | สตริงที่สี่เพื่อรวม |

### ค่าที่คืน

สตริงพารามิเตอร์ที่รวม

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function

แปลงอ็อบเจกต์หลายตัวเป็นสตริงและรวมสตริงที่ได้. การจำเพาะสำหรับชนิด [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) เพื่อแปลงและรวม |

### ค่าที่คืน

[String](../../system/string/) ค่าที่รวมจากการเป็นตัวแทนสตริงของอ็อบเจกต์ทั้งหมดที่ส่งมา

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function

แปลงอ็อบเจกต์หลายตัวเป็นสตริงและรวมสตริงที่ได้. การจำเพาะสำหรับชนิดเชิงเลข.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) เพื่อแปลงและรวม |

### ค่าที่คืน

[String](../../system/string/) ค่าที่รวมจากการเป็นตัวแทนสตริงของอ็อบเจกต์ทั้งหมดที่ส่งมา

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function

แปลงอ็อบเจกต์หลายตัวเป็นสตริงและรวมสตริงที่ได้. การจำเพาะสำหรับโครงสร้างและชนิดค่าต่าง ๆ.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) เพื่อแปลงและรวม |

### ค่าที่คืน

[String](../../system/string/) ค่าที่รวมจากการเป็นตัวแทนสตริงของอ็อบเจกต์ทั้งหมดที่ส่งมา

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::StringExtra](../)
* Library [Aspose.Slides](../../)