---
title: ToDateTime()
second_title: مرجع API Aspose.Slides برای C++
description: String را به معادل DateTime تبدیل می‌کند.
type: docs
weight: 417
url: /fa/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) متد

[String](../../../system/string/) را به معادل [DateTime](../../../system/datetime/) تبدیل می‌کند.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | رشته‌ای که باید تبدیل شود. |

### مقدار بازگشت

یک معادل [DateTime](../../../system/datetime/) از رشته.

## XmlConvert::ToDateTime(const String\&, const String\&) متد

[String](../../../system/string/) را به معادل [DateTime](../../../system/datetime/) تبدیل می‌کند.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | رشته‌ای که باید تبدیل شود. |
| format | const [String](../../../system/string/)\& | ساختار قالب برای اعمال به [DateTime](../../../system/datetime/) تبدیل شده. قالب‌های معتبر شامل "yyyy-MM-ddTHH:mm:sszzzzzz" و زیرمجموعه‌های آن هستند. رشته نسبت به این قالب اعتبارسنجی می‌شود. |

### مقدار بازگشت

یک معادل [DateTime](../../../system/datetime/) از رشته.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) متد

[String](../../../system/string/) را به معادل [DateTime](../../../system/datetime/) تبدیل می‌کند.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | رشته‌ای که باید تبدیل شود. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | آرایه‌ای حاوی ساختارهای قالب برای اعمال به [DateTime](../../../system/datetime/) تبدیل شده. قالب‌های معتبر شامل "yyyy-MM-ddTHH:mm:sszzzzzz" و زیرمجموعه‌های آن هستند. |

### مقدار بازگشت

یک معادل [DateTime](../../../system/datetime/) از رشته.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) متد

[String](../../../system/string/) را با استفاده از XmlDateTimeSerializationMode مشخص شده به [DateTime](../../../system/datetime/) تبدیل می‌کند.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | مقدار [String](../../../system/string/) که باید تبدیل شود. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | یکی از مقادیر شمارشی که مشخص می‌کند آیا تاریخ باید به زمان محلی تبدیل شود یا به عنوان زمان هماهنگ جهانی (UTC) حفظ شود، اگر تاریخ UTC باشد. |

### مقدار بازگشت

یک معادل [DateTime](../../../system/datetime/) از [String](../../../system/string/).

## موارد مرتبط

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)