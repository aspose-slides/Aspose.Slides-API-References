---
title: ConvertTo()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بتحويل الكائن إلى نوع محدد.
type: docs
weight: 14
url: /ar/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) طريقة

يقوم بتحويل الكائن إلى نوع محدد.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) معلومات سياق التحويل. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة عند تحويل الكائنات. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | كائن للتحويل. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | النوع للتحويل إليه. |

### قيمة الإرجاع

الكائن المحول.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [FontConverter](../)
* نطاق [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)