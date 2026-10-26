---
title: ConvertToString()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงอ็อบเจ็กต์เป็นสตริง.
type: docs
weight: 79
url: /th/system.componentmodel/typeconverter/converttostring/
---
## TypeConverter::ConvertToString(const System::SharedPtr\<System::Object\>\&) เมธอด

แปลงอ็อบเจ็กต์เป็นสตริง.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<System::Object> &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) เพื่อแปลง. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ที่แปลงแล้ว.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) เมธอด

แปลงอ็อบเจ็กต์เป็นสตริง.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) ข้อมูลบริบทการแปลง. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) เพื่อแปลง. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ที่แปลงแล้ว.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) เมธอด

แปลงอ็อบเจ็กต์เป็นสตริง.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) ข้อมูลบริบทการแปลง. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่จะใช้เมื่อแปลงอ็อบเจ็กต์. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) เพื่อแปลง. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ที่แปลงแล้ว.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [TypeConverter](../)
* คลาส [ITypeDescriptorContext](../../itypedescriptorcontext/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* เนมสเปซ [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)