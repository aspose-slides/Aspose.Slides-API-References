---
title: ConvertTo()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقوم بتحويل الكائن إلى نوع محدد.
type: docs
weight: 14
url: /ar/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) طريقة

يقوم بتحويل الكائن إلى نوع محدد.

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) معلومات سياق التحويل |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة عند تحويل الكائنات |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | كائن للتحويل. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | نوع للتحويل إليه. |

### قيمة الإرجاع

كائن محول.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [ImageConverter](../)
* مساحة الاسم [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)