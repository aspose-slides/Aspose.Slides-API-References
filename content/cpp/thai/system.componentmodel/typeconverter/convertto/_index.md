---
title: ConvertTo()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงวัตถุเป็นประเภทที่ระบุ.
type: docs
weight: 53
url: /th/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) เมธอด

แปลงวัตถุเป็นประเภทที่ระบุ.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) เพื่อแปลง. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | ประเภทที่จะทำการแปลงเป็น. |

### ค่าที่คืน

วัตถุที่แปลงแล้ว.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) เมธอด

แปลงวัตถุเป็นประเภทที่ระบุ.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) ข้อมูลบริบทการแปลง. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่จะใช้เมื่อแปลงวัตถุ. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) เพื่อแปลง. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | ประเภทที่จะทำการแปลงเป็น. |

### ค่าที่คืน

วัตถุที่แปลงแล้ว.

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [TypeConverter](../)
* คลาส [ITypeDescriptorContext](../../itypedescriptorcontext/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* เนมสเปซ [System::ComponentModel](../../)
* ไลบรารี [Aspose.Slides](../../../)