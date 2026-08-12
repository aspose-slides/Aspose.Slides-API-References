---
title: ConvertFromString()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แปลงสตริงเป็นอ็อบเจ็กต์.
type: docs
weight: 40
url: /th/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) method

แปลงสตริงเป็นอ็อบเจกต์.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | ค่าที่จะทำการแปลง |

### ค่าที่ส่งกลับ

อ็อบเจกต์ที่แปลงแล้ว.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) method

แปลงสตริงเป็นอ็อบเจกต์.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) ข้อมูลบริบทการแปลง |
| text | const [System::String](../../../system/string/)\& | ค่าที่จะทำการแปลง |

### ค่าที่ส่งกลับ

อ็อบเจกต์ที่แปลงแล้ว.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) method

แปลงสตริงเป็นอ็อบเจกต์.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) ข้อมูลบริบทการแปลง |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่จะใช้เมื่อต้องแปลงอ็อบเจกต์ |
| text | const [System::String](../../../system/string/)\& | ค่าที่จะทำการแปลง |

### ค่าที่ส่งกลับ

อ็อบเจกต์ที่แปลงแล้ว.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [String](../../../system/string/)
* คลาส [TypeConverter](../)
* คลาส [ITypeDescriptorContext](../../itypedescriptorcontext/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* เนมสเปซ [System::ComponentModel](../../)
* ไลบรารี [Aspose.Slides](../../../)