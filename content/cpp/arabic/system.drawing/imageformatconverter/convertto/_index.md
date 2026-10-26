---
title: ConvertTo()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتحويل الكائن إلى نوع محدد.
type: docs
weight: 27
url: /ar/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) طريقة

يقوم بتحويل الكائن إلى نوع محدد.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) معلومات سياق التحويل. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة عند تحويل الكائنات. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) للتحويل. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | النوع للتحويل إليه. |

### قيمة الإرجاع

الكائن المحول.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [ImageFormatConverter](../)
* نطاق [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)