---
title: ConvertFromString()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتحويل السلسلة إلى كائن.
type: docs
weight: 40
url: /ar/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) طريقة

Converts string to object.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | القيمة للتحويل. |

### قيمة الإرجاع

الكائن المحول.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) طريقة

Converts string to object.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) معلومات سياق التحويل. |
| text | const [System::String](../../../system/string/)\& | القيمة للتحويل. |

### قيمة الإرجاع

الكائن المحول.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) طريقة

Converts string to object.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) معلومات سياق التحويل. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة عند تحويل الكائنات. |
| text | const [System::String](../../../system/string/)\& | القيمة للتحويل. |

### قيمة الإرجاع

الكائن المحول.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [TypeConverter](../)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)