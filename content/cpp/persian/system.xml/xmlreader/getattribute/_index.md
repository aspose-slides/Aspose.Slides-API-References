---
title: GetAttribute()
second_title: مرجع API Aspose.Slides برای C++
description: "زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، مقدار ویژگی با مقدار XmlReader::get_Name مشخص‌شده را دریافت می‌کند."
type: docs
weight: 599
url: /fa/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) متد


زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، مقدار ویژگی با مقدار [XmlReader::get_Name](../get_name/) مشخص‌شده را دریافت می‌کند.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام معتبر ویژگی. |

### مقدار بازگشت

مقدار ویژگی مشخص‌شده. اگر ویژگی پیدا نشد یا مقدار آن [String::Empty](../../../system/string/empty/) باشد، **nullptr** برگردانده می‌شود.

## XmlReader::GetAttribute(String, String) متد


زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، مقدار ویژگی با مقدار [XmlReader::get_LocalName](../get_localname/) و [XmlReader::get_NamespaceURI](../get_namespaceuri/) مشخص‌شده را دریافت می‌کند.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام ویژگی. |

### مقدار بازگشت

مقدار ویژگی مشخص‌شده. اگر ویژگی پیدا نشد یا مقدار آن [String::Empty](../../../system/string/empty/) باشد، **nullptr** برگردانده می‌شود. این متد خواننده را جابجا نمی‌کند.

## XmlReader::GetAttribute(int32_t) متد


زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، مقدار ویژگی با شاخص مشخص‌شده را دریافت می‌کند.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| i | **int32_t** | شاخص ویژگی. شاخص از صفر شروع می‌شود. (اولین ویژگی شاخص 0 دارد.) |

### مقدار بازگشت

مقدار ویژگی مشخص‌شده. این متد خواننده را جابجا نمی‌کند.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)