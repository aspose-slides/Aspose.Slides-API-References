---
title: ConvertTo()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงวัตถุเป็นประเภทที่ระบุ.
type: docs
weight: 27
url: /th/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) เมธอด


แปลงวัตถุเป็นประเภทที่ระบุ.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) ข้อมูลบริบทการแปลง. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่จะใช้เมื่อแปลงวัตถุ. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) เพื่อแปลง. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทที่จะแปลงเป็น. |

### Return Value

วัตถุนั้นที่แปลงแล้ว.

## ดูเพิ่มเติม

* typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [ImageFormatConverter](../)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)