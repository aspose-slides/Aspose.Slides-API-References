---
title: ConvertTo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل الكائن إلى نوع محدد.
type: docs
weight: 53
url: /ar/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) طريقة

يقوم بتحويل الكائن إلى نوع محدد.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) للتحويل. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | نوع للتحويل إليه. |

### قيمة الإرجاع

الكائن المحول.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) طريقة

يقوم بتحويل الكائن إلى نوع محدد.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) معلومات سياق التحويل. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة عند تحويل الكائنات. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) للتحويل. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | نوع للتحويل إليه. |

### قيمة الإرجاع

الكائن المحول.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [TypeConverter](../)
* فئة [ITypeDescriptorContext](../../itypedescriptorcontext/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* مساحة اسم [System::ComponentModel](../../)
* مكتبة [Aspose.Slides](../../../)