---
title: GetAttribute()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار ویژگی با نام مشخص‌شده را برمی‌گرداند.
type: docs
weight: 495
url: /fa/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) method

مقدار ویژگی با نام مشخص‌شده را برمی‌گرداند.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام کامل ویژگی. |

### مقدار بازگشتی

مقدار ویژگی مشخص‌شده. اگر ویژگی یافت نشود، **nullptr** برگردانده می‌شود.

## XmlTextReader::GetAttribute(String, String) method

مقدار ویژگی با نام محلی و URI فضای‌نام مشخص‌شده را برمی‌گرداند.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای‌نام ویژگی. |

### مقدار بازگشتی

مقدار ویژگی مشخص‌شده. اگر ویژگی یافت نشود، **nullptr** برگردانده می‌شود. این متد خواننده را جابه‌جا نمی‌کند.

## XmlTextReader::GetAttribute(int32_t) method

مقدار ویژگی با اندیس مشخص‌شده را برمی‌گرداند.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | اندیس ویژگی. اندیس صفر-مبنایی است. (ویژگی اول دارای اندیس 0 است.) |

### مقدار بازگشتی

مقدار ویژگی مشخص‌شده.

## موارد مرتبط

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)