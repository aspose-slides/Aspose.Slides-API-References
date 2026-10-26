---
title: ConvertFromString()
second_title: Aspose.Slides برای C++ مرجع API
description: رشته را به شی تبدیل می‌کند.
type: docs
weight: 40
url: /fa/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) متد

رشته را به شی تبدیل می‌کند.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | مقدار برای تبدیل. |

### مقدار بازگشتی

شی تبدیل‌شده.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) متد

رشته را به شی تبدیل می‌کند.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) اطلاعات زمینه تبدیل. |
| text | const [System::String](../../../system/string/)\& | مقدار برای تبدیل. |

### مقدار بازگشتی

شی تبدیل‌شده.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) متد

رشته را به شی تبدیل می‌کند.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) اطلاعات زمینه تبدیل. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | فرهنگی که هنگام تبدیل اشیا استفاده می‌شود. |
| text | const [System::String](../../../system/string/)\& | مقدار برای تبدیل. |

### مقدار بازگشتی

شی تبدیل‌شده.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [String](../../../system/string/)
* کلاس [TypeConverter](../)
* کلاس [ITypeDescriptorContext](../../itypedescriptorcontext/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* فضای‌نام [System::ComponentModel](../../)
* کتابخانه [Aspose.Slides](../../../)