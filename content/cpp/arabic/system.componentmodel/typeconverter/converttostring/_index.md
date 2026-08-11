---
title: ConvertToString()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحوّل الكائن إلى سلسلة.
type: docs
weight: 79
url: /ar/system.componentmodel/typeconverter/converttostring/
---
## TypeConverter::ConvertToString(const System::SharedPtr\<System::Object\>\&) طريقة

يحوّل الكائن إلى سلسلة.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<System::Object> &value)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) للتحويل. |

### القيمة المرجعة

الكائن المحوّل.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) طريقة

يحوّل الكائن إلى سلسلة.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) معلومات سياق التحويل. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) للتحويل. |

### القيمة المرجعة

الكائن المحوّل.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) طريقة

يحوّل الكائن إلى سلسلة.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) معلومات سياق التحويل. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة عند تحويل الكائنات. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) للتحويل. |

### القيمة المرجعة

الكائن المحوّل.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [Object](../../../system/object/)
* فئة [TypeConverter](../)
* فئة [ITypeDescriptorContext](../../itypedescriptorcontext/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* مساحة الاسم [System::ComponentModel](../../)
* مكتبة [Aspose.Slides](../../../)