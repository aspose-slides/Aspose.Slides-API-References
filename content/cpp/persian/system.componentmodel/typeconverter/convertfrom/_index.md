---
title: ConvertFrom()
second_title: مرجع API Aspose.Slides برای C++
description: اشیاء را تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) متد

اشیاء را تبدیل می‌کند.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) برای تبدیل. |

### مقدار بازگشتی

شیء تبدیل‌شده.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) متد

اشیاء را تبدیل می‌کند.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) اطلاعات زمینه تبدیل. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | فرهنگی که هنگام تبدیل اشیاء استفاده می‌شود. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) برای تبدیل. |

### مقدار بازگشتی

شیء تبدیل‌شده.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) متد

رشته را به شیء تبدیل می‌کند.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) اطلاعات زمینه تبدیل. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | فرهنگی که هنگام تبدیل اشیاء استفاده می‌شود. |
| value | const [System::String](../../../system/string/)\& | مقدار برای تبدیل. |

### مقدار بازگشتی

شیء تبدیل‌شده.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [TypeConverter](../)
* کلاس [ITypeDescriptorContext](../../itypedescriptorcontext/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::ComponentModel](../../)
* کتابخانه [Aspose.Slides](../../../)