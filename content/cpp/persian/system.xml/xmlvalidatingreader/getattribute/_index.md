---
title: GetAttribute()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار ویژگی با نام مشخص‌شده را برمی‌گرداند.
type: docs
weight: 443
url: /fa/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) متد

مقدار ویژگی با نام مشخص‌شده را برمی‌گرداند.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام معتبر ویژگی. |

### مقدار بازگشت

مقدار ویژگی مشخص‌شده. اگر ویژگی یافت نشد، **nullptr** برگردانده می‌شود.

## XmlValidatingReader::GetAttribute(String, String) متد

مقدار ویژگی با نام محلی و شناسهٔ منبع یکتا (URI) فضای نام مشخص‌شده را برمی‌گرداند.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام ویژگی. |

### مقدار بازگشت

مقدار ویژگی مشخص‌شده. اگر ویژگی یافت نشد، **nullptr** برگردانده می‌شود. این متد خواننده را جابجا نمی‌کند.

## XmlValidatingReader::GetAttribute(int32_t) متد

مقدار ویژگی با ایندکس مشخص‌شده را برمی‌گرداند.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| i | **int32_t** | ایندکس ویژگی. ایندکس صفر-مبنایی است. (اولین ویژگی ایندکس 0 دارد.) |

### مقدار بازگشت

مقدار ویژگی مشخص‌شده.

## مراجع مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlValidatingReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)