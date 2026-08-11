---
title: StringWriter()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از StringWriter را با استفاده از StringBuilder مشخص‌شده و IFormatProvider می‌سازد.
type: docs
weight: 1
url: /fa/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) سازنده

یک نمونه جدید از [StringWriter](../) را با استفاده از StringBuilder مشخص‌شده و [IFormatProvider](../../../system/iformatprovider/) می‌سازد.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | شیء StringBuilder که توسط [StringWriter](../) در حال ساخت استفاده خواهد شد |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | شیء [IFormatProvider](../../../system/iformatprovider/) برای استفاده توسط شیء در حال ساخت |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) سازنده

یک نمونه جدید از [StringWriter](../) را با استفاده از StringBuilder مشخص‌شده و [IFormatProvider](../../../system/iformatprovider/) از فرهنگ جاری می‌سازد.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | شیء StringBuilder که توسط [StringWriter](../) در حال ساخت استفاده خواهد شد |

## StringWriter::StringWriter(const IFormatProviderPtr\&) سازنده

یک نمونه جدید از [StringWriter](../) را با استفاده از [IFormatProvider](../../../system/iformatprovider/) مشخص‌شده می‌سازد.

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | شیء [IFormatProvider](../../../system/iformatprovider/) برای استفاده توسط شیء در حال ساخت |

## StringWriter::StringWriter() سازنده

یک نمونه جدید از [StringWriter](../) را با استفاده از [IFormatProvider](../../../system/iformatprovider/) از فرهنگ جاری می‌سازد.

```cpp
System::IO::StringWriter::StringWriter()
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* کلاس [StringBuilder](../../../system.text/stringbuilder/)
* کلاس [StringWriter](../)
* فضای‌نام [System::IO](../../)
* Library [Aspose.Slides](../../../)