---
title: ConvertFrom()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتحويل الكائنات.
type: docs
weight: 14
url: /ar/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) طريقة

يقوم بتحويل الكائنات.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) للتحويل. |

### قيمة الإرجاع

الكائن المحول.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) طريقة

يقوم بتحويل الكائنات.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) معلومات سياق التحويل. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة عند تحويل الكائنات. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) للتحويل. |

### قيمة الإرجاع

الكائن المحول.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) طريقة

يقوم بتحويل السلسلة إلى كائن.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) معلومات سياق التحويل. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة عند تحويل الكائنات. |
| value | const [System::String](../../../system/string/)\& | القيمة للتحويل. |

### قيمة الإرجاع

الكائن المحول.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [TypeConverter](../)
* فئة [ITypeDescriptorContext](../../itypedescriptorcontext/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [String](../../../system/string/)
* نطاق [System::ComponentModel](../../)
* مكتبة [Aspose.Slides](../../../)