---
title: GetAttribute()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار ویژگی با نام مشخص‌شده را برمی‌گرداند.
type: docs
weight: 287
url: /fa/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) متد

مقدار ویژگی با نام مشخص‌شده را برمی‌گرداند.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام مؤهل ویژگی. |

### Return Value

مقدار ویژگی مشخص‌شده. اگر ویژگی پیدا نشود، **nullptr** برگردانده می‌شود.

## XmlNodeReader::GetAttribute(String, String) متد

مقدار ویژگی با نام محلی و URI فضای‌نامی مشخص‌شده را برمی‌گرداند.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای‌نامی ویژگی. |

### Return Value

مقدار ویژگی مشخص‌شده. اگر ویژگی پیدا نشود، **nullptr** برگردانده می‌شود.

## XmlNodeReader::GetAttribute(int32_t) متد

مقدار ویژگی با ایندکس مشخص‌شده را برمی‌گرداند.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| attributeIndex | **int32_t** | ایندکس ویژگی. ایندکس از صفر شروع می‌شود. (ویژگی اول ایندکس 0 دارد.) |

### Return Value

مقدار ویژگی مشخص‌شده.

## See Also

* کلاس [String](../../../system/string/)
* کلاس [XmlNodeReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)