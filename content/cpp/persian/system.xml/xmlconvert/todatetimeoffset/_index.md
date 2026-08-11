---
title: ToDateTimeOffset()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار String ارائه‌شده را به معادل DateTimeOffset تبدیل می‌کند.
type: docs
weight: 430
url: /fa/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) متد


مقدار [String](../../../system/string/) ارائه‌شده را به معادل [DateTimeOffset](../../../system/datetimeoffset/) تبدیل می‌کند.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | رشته‌ای که باید تبدیل شود. این رشته باید با زیرمجموعه‌ای از توصیه‌نامه W3C برای نوع XML dateTime هم‌خوانی داشته باشد. برای اطلاعات بیشتر، بخش [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) از مشخصات XML [Schema](../../../system.xml.schema/) را ببینید. |

### مقدار بازگشت

معادل [DateTimeOffset](../../../system/datetimeoffset/) رشته ارائه‌شده.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) متد


مقدار [String](../../../system/string/) ارائه‌شده را به معادل [DateTimeOffset](../../../system/datetimeoffset/) تبدیل می‌کند.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | رشته‌ای که باید تبدیل شود. |
| format | const [String](../../../system/string/)\& | قالبی که از آن **s** تبدیل می‌شود. پارامتر قالب می‌تواند هر زیرمجموعه‌ای از توصیه‌نامه W3C برای نوع XML dateTime باشد. برای اطلاعات بیشتر، بخش [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) از مشخصات XML [Schema](../../../system.xml.schema/) را ببینید. رشته **s** بر اساس این قالب اعتبارسنجی می‌شود. |

### مقدار بازگشت

معادل [DateTimeOffset](../../../system/datetimeoffset/) رشته ارائه‌شده.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) متد


مقدار [String](../../../system/string/) ارائه‌شده را به معادل [DateTimeOffset](../../../system/datetimeoffset/) تبدیل می‌کند.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | رشته‌ای که باید تبدیل شود. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | آرایه‌ای از قالب‌ها که از آن‌ها می‌توان **s** را تبدیل کرد. هر قالب در **formats** می‌تواند هر زیرمجموعه‌ای از توصیه‌نامه W3C برای نوع XML dateTime باشد. برای اطلاعات بیشتر، بخش [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) از مشخصات XML [Schema](../../../system.xml.schema/) را ببینید. رشته **s** بر اساس یکی از این قالب‌ها اعتبارسنجی می‌شود. |

### مقدار بازگشت

معادل [DateTimeOffset](../../../system/datetimeoffset/) رشته ارائه‌شده.

## مراجع

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [DateTimeOffset](../../../system/datetimeoffset/)
* کلاس [String](../../../system/string/)
* کلاس [XmlConvert](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)