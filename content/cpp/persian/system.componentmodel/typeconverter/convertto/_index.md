---
title: ConvertTo()
second_title: Aspose.Slides برای C++ مرجع API
description: شی را به نوع خاص تبدیل می‌کند.
type: docs
weight: 53
url: /fa/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) متد

یک شی را به نوع خاص تبدیل می‌کند.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) برای تبدیل. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | نوعی که به آن تبدیل می‌شود. |

### مقدار بازگشتی

شی تبدیل‌شده.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) متد

یک شی را به نوع خاص تبدیل می‌کند.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) اطلاعات زمینه تبدیل. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | فرهنگی که هنگام تبدیل اشیاء استفاده می‌شود. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) برای تبدیل. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | نوعی که به آن تبدیل می‌شود. |

### مقدار بازگشتی

شی تبدیل‌شده.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [TypeConverter](../)
* کلاس [ITypeDescriptorContext](../../itypedescriptorcontext/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* فضای‌نام [System::ComponentModel](../../)
* کتابخانه [Aspose.Slides](../../../)