---
title: ConvertTo()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงอ็อบเจ็กต์เป็นประเภทเฉพาะ.
type: docs
weight: 14
url: /th/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) เมธอด

แปลงอ็อบเจ็กต์เป็นประเภทที่ระบุ

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) ข้อมูลบริบทการแปลง |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่ใช้เมื่อแปลงอ็อบเจ็กต์ |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | อ็อบเจ็กต์ที่จะทำการแปลง |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | ประเภทที่ต้องการแปลงเป็น |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ที่แปลงแล้ว

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [ImageConverter](../)
* เนมสเปซ [System::Drawing](../../)
* Library [Aspose.Slides](../../../)