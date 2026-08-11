---
title: ToString()
second_title: Aspose.Slides برای مرجع API C++
description: معادل متد Object.ToString() در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند.
type: docs
weight: 79
url: /fa/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const متد

معادل متد C# [Object.ToString()](../../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### مقدار بازگشت

[String](../../../system/string/) نمایش به‌دست‌آمده توسط کلاس نهایی.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) متد

نمایش رشته‌ای از مجموعه نمونه‌های کلاس NameValueHeaderValue را برمی‌گرداند.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | مجموعه‌ای از نمونه‌های کلاس NameValueHeaderValue. |
| separator | char16_t | یک جداکننده رشته. |
| leadingSeparator | **bool** | مقداری که نشان می‌دهد آیا جداکننده رشته باید پیش از اولین عنصر مجموعه اضافه شود. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | نمونه‌ای که نمایش رشته‌ای به آن اختصاص خواهد یافت. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) متد

نمایش رشته‌ای از مجموعه نمونه‌های کلاس NameValueHeaderValue را برمی‌گرداند.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | مجموعه‌ای از نمونه‌های کلاس NameValueHeaderValue. |
| separator | char16_t | یک جداکننده رشته. |
| leadingSeparator | **bool** | مقداری که نشان می‌دهد آیا جداکننده رشته باید پیش از اولین عنصر مجموعه اضافه شود. |

### مقدار بازگشت

نمایش رشته‌ای از مجموعه نمونه‌های کلاس NameValueHeaderValue.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [NameValueHeaderValue](../)
* کلاس [ObjectCollection](../../objectcollection/)
* کلاس [StringBuilder](../../../system.text/stringbuilder/)
* فضای نام [System::Net::Http::Headers](../../)
* کتابخانه [Aspose.Slides](../../../)