---
title: ConvertFromInvariantString()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงคงที่เป็นอ็อบเจกต์.
type: docs
weight: 27
url: /th/system.componentmodel/typeconverter/convertfrominvariantstring/
---
## TypeConverter::ConvertFromInvariantString(const System::String\&) เมธอด

แปลงสตริงคงที่เป็นอ็อบเจกต์.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::String &text)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | ค่าที่ต้องการแปลง. |

### ค่าที่ส่งคืน

อ็อบเจกต์ที่แปลงแล้ว.

## TypeConverter::ConvertFromInvariantString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) เมธอด

แปลงสตริงคงที่เป็นอ็อบเจกต์.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) ข้อมูลบริบทการแปลง. |
| text | const [System::String](../../../system/string/)\& | ค่าที่ต้องการแปลง. |

### ค่าที่ส่งคืน

อ็อบเจกต์ที่แปลงแล้ว.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [String](../../../system/string/)
* คลาส [TypeConverter](../)
* คลาส [ITypeDescriptorContext](../../itypedescriptorcontext/)
* เนมสเปซ [System::ComponentModel](../../)
* ไลบรารี [Aspose.Slides](../../../)